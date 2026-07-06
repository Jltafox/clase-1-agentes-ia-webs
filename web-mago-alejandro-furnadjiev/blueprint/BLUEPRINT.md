# BLUEPRINT — Arquitectura de la web

> **Estado: BORRADOR v0.** Se cerrará tras la fase de investigación de competidores y la confirmación de la zona de actuación.
> Regla: ninguna página se genera sin tener aquí su title, meta description, H1 y schema.

## Objetivo de negocio

Conseguir **solicitudes de presupuesto** para dos servicios en **Madrid**: actuaciones para eventos de empresa y para eventos privados de adultos. Conversión principal: formulario de contacto + WhatsApp.

## Mapa de URLs (v0)

| URL | Página | Intención de búsqueda objetivo |
|-----|--------|-------------------------------|
| `/` | Home | "mago para eventos madrid", "mago madrid", marca |
| `/eventos-empresa/` | Landing servicio | "mago para eventos de empresa madrid", "magia para cenas de empresa", "mago team building madrid" |
| `/eventos-privados/` | Landing servicio | "mago para fiestas privadas madrid", "mago para cumpleaños de adultos madrid", "magia de cerca para eventos" |
| `/sobre-alejandro/` | Bio + credenciales | marca, confianza |
| `/contacto/` | Formulario + WhatsApp | conversión |
| `/[servicio]/[zona]/` | *(futuro)* landings locales | patrón servicio × zona/municipio del área de Madrid, tras la investigación |

**Descartado de todo el análisis** (decisión 2026-07-06): magia infantil, cumpleaños infantiles y comuniones — no se crean URLs ni contenido. Fuera de alcance: todo lo relativo a la escuela online.

## Estructura por página (v0)

### Home `/`

1. Hero: titular con propuesta de valor + CTA "Pide presupuesto" + CTA WhatsApp.
2. Press bar de credenciales (Almería 1999 · FLASOMA 2004 · Memorial Ascanio 2006 · profesor Escuela Ana Tamariz).
3. Dos tarjetas de servicio → landings.
4. Bloque "Sobre Alejandro" resumido + foto `[PENDIENTE]`.
5. Testimonios `[PENDIENTE: reales]`.
6. CTA final + FAQ corta.

### `/eventos-empresa/`

Hero elegante oscuro · formatos (magia de cerca entre mesas, escenario, team building, congresos) `[PENDIENTE: confirmar formatos reales]` · credenciales en profundidad · logos de clientes `[PENDIENTE]` · FAQ (aforo, duración, requisitos técnicos, desplazamiento) · CTA.

### `/eventos-privados/`

Hero elegante · tipos de celebración (cumpleaños de adultos, fiestas privadas, bodas) `[PENDIENTE: confirmar tipos exactos con el cliente]` · por qué magia de cerca de un mago premiado transforma una celebración · testimonios `[PENDIENTE]` · FAQ (espacio necesario, duración, nº de invitados) · CTA.

### `/sobre-alejandro/`

Bio narrativa desde `memory/user_alejandro-furnadjiev.md`: Ascanio, Tamariz, premios, 20+ años, docencia. Foto retrato `[PENDIENTE]`.

## SEO técnico

- **Schema.org**: `Person` (Alejandro, en `/sobre-alejandro/` y home) + `LocalBusiness`/`Service` por landing + `FAQPage` en FAQs. Plantillas JSON-LD se añadirán en `blueprint/schema-templates/`.
- **Meta**: title ≤ 60 car., description ≤ 155 car., un solo H1 por página. Se redactarán al cerrar keywords (post-investigación).
- **Performance**: presupuesto Lighthouse ≥ 90 en las 4 categorías; imágenes AVIF/WebP con `srcset`; cero JS innecesario (Astro islands solo si hace falta).
- **Interlinking**: home ↔ landings ↔ sobre ↔ contacto; futuras landings locales cuelgan de su servicio.

## Pendiente para v1 (cerrar blueprint)

- [ ] Investigación de competidores en Madrid (skills `serp-pattern-detector` + `competitor-local-seo-audit` del repo de la clase) → patrones de las webs de magos que ya posicionan para "mago eventos empresa madrid" y afines.
- [ ] Decidir si hacen falta landings por zona/municipio del área de Madrid o basta con Madrid ciudad.
- [ ] Redactar titles/descriptions/H1 por página.
- [ ] Plantillas JSON-LD (`LocalBusiness` con `areaServed: Madrid`).

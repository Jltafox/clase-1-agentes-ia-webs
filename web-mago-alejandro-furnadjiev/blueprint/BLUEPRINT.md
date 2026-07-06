# BLUEPRINT — Arquitectura de la web

> **Estado: BORRADOR v0.1** — actualizado con la investigación de competidores del 2026-07-06 (ver `data/investigacion/2026-07-06/`). Pendiente para v1: validación técnica de SERP con geo real y decisiones del cliente.
> Regla: ninguna página se genera sin tener aquí su title, meta description, H1 y schema.

## Posicionamiento (derivado de la investigación)

Cada competidor top tiene un ángulo propio (tecnología, humor, elegancia). El de Alejandro, que nadie en la SERP puede replicar: **discípulo directo de Arturo de Ascanio y Juan Tamariz, con Gran Premio internacional de cartomagia (FLASOMA 2004) y Memorial Ascanio 2006** → "magia de cerca de élite, heredera de la gran escuela madrileña". Titles sin símbolos ni emojis (patrón de agencia, no de mago premium).

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
| `/precios/` *(propuesta, hipótesis H4)* | Precios orientativos o guía "cuánto cuesta" | "cuánto cuesta contratar un mago madrid", "precio mago madrid" |
| `/[servicio]/[zona]/` | *(futuro, hipótesis H7)* landings por municipio (Alcobendas, Pozuelo, Las Rozas…) | post-lanzamiento, si hay tracción |

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

- [x] Investigación de competidores en Madrid → **hecha 2026-07-06** (con limitaciones de red documentadas). Resultados en `data/investigacion/2026-07-06/`.
- [ ] Validación técnica pendiente: SERP con geo Madrid + móvil, Lighthouse y schema de los 6 competidores individuales, datos GBP (bloqueado por la red del entorno actual).
- [ ] Decisión del cliente: ¿publicar precios orientativos? (hipótesis H4 — los que lo hacen ganan la SERP de precio).
- [ ] Decisión del cliente: ¿incluir bodas dentro de eventos privados? (todos los comparables las trabajan).
- [ ] Formatos reales de actuación (duración, aforo) para las landings — hipótesis H3.
- [ ] Landings por municipio: pospuesto a post-lanzamiento (hipótesis H7).
- [ ] Redactar titles/descriptions/H1 por página (patrón: `[Servicio] en Madrid | Alejandro Furnadjiev`, sin símbolos).
- [ ] Plantillas JSON-LD (`LocalBusiness` con `areaServed: Madrid`).

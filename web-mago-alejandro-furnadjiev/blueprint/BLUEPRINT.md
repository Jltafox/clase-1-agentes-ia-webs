# BLUEPRINT — Arquitectura de la web

> **Estado: BORRADOR v0.** Se cerrará tras la fase de investigación de competidores y la confirmación de la zona de actuación.
> Regla: ninguna página se genera sin tener aquí su title, meta description, H1 y schema.

## Objetivo de negocio

Conseguir **solicitudes de presupuesto** para dos servicios: espectáculos de magia infantil (cumpleaños) y actuaciones para eventos de empresa. Conversión principal: formulario de contacto + WhatsApp.

## Mapa de URLs (v0)

| URL | Página | Intención de búsqueda objetivo |
|-----|--------|-------------------------------|
| `/` | Home | "mago para eventos [ciudad]", marca |
| `/magia-infantil/` | Landing servicio | "mago para cumpleaños infantiles [ciudad]", "mago infantil" |
| `/eventos-empresa/` | Landing servicio | "mago para eventos de empresa", "magia para cenas de empresa", "mago team building" |
| `/sobre-alejandro/` | Bio + credenciales | marca, confianza |
| `/contacto/` | Formulario + WhatsApp | conversión |
| `/[servicio]/[ciudad]/` | *(futuro)* landings locales | patrón servicio × ciudad cuando se confirme la zona |

Descartado: `/comuniones/` (decisión 2026-07-06). Fuera de alcance: todo lo relativo a la escuela online.

## Estructura por página (v0)

### Home `/`

1. Hero: titular con propuesta de valor + CTA "Pide presupuesto" + CTA WhatsApp.
2. Press bar de credenciales (Almería 1999 · FLASOMA 2004 · Memorial Ascanio 2006 · profesor Escuela Ana Tamariz).
3. Dos tarjetas de servicio → landings.
4. Bloque "Sobre Alejandro" resumido + foto `[PENDIENTE]`.
5. Testimonios `[PENDIENTE: reales]`.
6. CTA final + FAQ corta.

### `/magia-infantil/`

Hero cálido (variante clara de `DESIGN.md`) · qué incluye el espectáculo `[PENDIENTE: formato/duración]` · para qué edades · por qué un mago premiado y no un animador genérico · testimonios · FAQ (espacio, duración, nº de niños, desplazamiento) · CTA.

### `/eventos-empresa/`

Hero elegante oscuro · formatos (magia de cerca entre mesas, escenario, team building) `[PENDIENTE: confirmar formatos reales]` · credenciales en profundidad · logos de clientes `[PENDIENTE]` · FAQ (aforo, duración, requisitos técnicos) · CTA.

### `/sobre-alejandro/`

Bio narrativa desde `memory/user_alejandro-furnadjiev.md`: Ascanio, Tamariz, premios, 20+ años, docencia. Foto retrato `[PENDIENTE]`.

## SEO técnico

- **Schema.org**: `Person` (Alejandro, en `/sobre-alejandro/` y home) + `LocalBusiness`/`Service` por landing + `FAQPage` en FAQs. Plantillas JSON-LD se añadirán en `blueprint/schema-templates/`.
- **Meta**: title ≤ 60 car., description ≤ 155 car., un solo H1 por página. Se redactarán al cerrar keywords (post-investigación).
- **Performance**: presupuesto Lighthouse ≥ 90 en las 4 categorías; imágenes AVIF/WebP con `srcset`; cero JS innecesario (Astro islands solo si hace falta).
- **Interlinking**: home ↔ landings ↔ sobre ↔ contacto; futuras landings locales cuelgan de su servicio.

## Pendiente para v1 (cerrar blueprint)

- [ ] Confirmar ciudad/zona → keywords locales definitivas.
- [ ] Investigación de competidores (skills `serp-pattern-detector` + `competitor-local-seo-audit` del repo de la clase) → patrones de las webs que ya posicionan.
- [ ] Redactar titles/descriptions/H1 por página.
- [ ] Plantillas JSON-LD.

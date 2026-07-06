# Web · Mago Alejandro Furnadjiev

> Web de servicios de mago para eventos: **magia infantil (cumpleaños)** y **eventos de empresa**.
> Proyecto estructurado con el arnés de agentes de [arnes-agentes/global](https://github.com/genteinvencible/arnes-agentes/tree/main/global) y el flujo de trabajo de la Clase 1 de YinyangSEO.

---

## ⚠️ Estado del proyecto

**Fase actual: Fundacional.** Arnés montado, blueprint en borrador. Todavía **no hay código de la web** — falta investigación de competidores y confirmación de datos del cliente (ver `memory/project_web-mago.md`).

## Alcance

| Incluido | Excluido (por ahora) |
|----------|----------------------|
| Magia infantil / cumpleaños | Comuniones (descartado) |
| Eventos de empresa (cenas, team building, congresos) | Escuela online Método Furni |
| Página "Sobre Alejandro" + contacto | Venta de productos / suscripciones |

## Mapa del repositorio

| Ruta | Qué contiene | Cuándo consultarlo |
|------|--------------|--------------------|
| `AGENTS.md` | Mapa del proyecto para agentes: stack, comandos, reglas | **Siempre, al empezar cualquier sesión** |
| `CLAUDE.md` | Dinámica de trabajo y reglas de colaboración | Al empezar sesión |
| `DESIGN.md` | Sistema de diseño: tokens, lenguaje visual | Antes de tocar UI |
| `MEMORY.md` | Índice de memoria persistente | Al empezar sesión |
| `memory/` | Perfil del cliente, estado del proyecto, fuentes | Según indique `MEMORY.md` |
| `blueprint/BLUEPRINT.md` | Arquitectura de la web, URLs, SEO | Antes de generar cualquier página |

## Flujo de trabajo previsto

1. **Investigación** — competidores locales (magos infantiles / de empresa) con las skills del curso (`serp-pattern-detector`, `competitor-local-seo-audit`).
2. **Blueprint** — cerrar arquitectura, keywords y schema en `blueprint/BLUEPRINT.md`.
3. **Generación** — scaffolding Astro + landings por servicio.
4. **QA + Deploy** — Lighthouse, schema válido, deploy en Vercel/Netlify.

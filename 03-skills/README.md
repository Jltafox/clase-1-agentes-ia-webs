# Skills · Flujo completo SEO agéntico

> 11 skills que cubren el ciclo completo: desde investigar el Local Pack hasta tener una web desplegada y auditada.

---

## Leyenda

| Símbolo | Significado |
|:-------:|-------------|
| ✅ MADURA | Lista para usar con un caso real. Entregable definido. |
| 🟡 STUB | Estructura completa lista para que tu agente la implemente. |

---

## Tabla de skills

| # | Skill | Estado | Fase | Qué hace |
|---|-------|:------:|------|----------|
| 1 | [`local-pack-multi-city`](local-pack-multi-city/SKILL.md) | 🟡 STUB | Investigación | Captura Local Pack y orgánico Google en N ciudades, consolida negocios únicos. |
| 2 | [`serp-pattern-detector`](serp-pattern-detector/SKILL.md) | ✅ MADURA | Investigación | Analiza una SERP detectando patrones Google sobre contenido, schema, freshness y dominio. |
| 3 | [`gbp-grid-extractor`](gbp-grid-extractor/SKILL.md) | ✅ MADURA | Investigación | Genera grid geográfico de rankings GBP para medir visibilidad local por zonas. |
| 4 | [`gbp-deep-profile`](gbp-deep-profile/SKILL.md) | 🟡 STUB | Análisis | Extrae ficha completa Google Business Profile: categorías, atributos, fotos, posts, reseñas. |
| 5 | [`web-pattern-extractor`](web-pattern-extractor/SKILL.md) | 🟡 STUB | Análisis | Escanea N webs y genera matriz comparativa de schema, headings, secciones y Lighthouse. |
| 6 | [`competitor-local-seo-audit`](competitor-local-seo-audit/SKILL.md) | ✅ MADURA | Análisis | Auditoría SEO local exhaustiva de un competidor, entregable en formato informe profesional. |
| 7 | [`local-seo-pattern-aggregator`](local-seo-pattern-aggregator/SKILL.md) | 🟡 STUB | Patrones | Detecta qué hacen diferente las webs ganadoras del Local Pack cruzando datos de fases 1–2. |
| 8 | [`web-blueprint-generator`](web-blueprint-generator/SKILL.md) | 🟡 STUB | Blueprint | Convierte hipótesis de patrones en blueprint web: URLs, schema, secciones e internal linking. |
| 9 | [`landing-generator-servicio-barrio`](landing-generator-servicio-barrio/SKILL.md) | 🟡 STUB | Generación | Genera páginas servicio × barrio en Astro con schema JSON-LD e internal linking automático. |
| 10 | [`landing-qa-runner`](landing-qa-runner/SKILL.md) | 🟡 STUB | QA + Deploy | Verifica landings con Playwright, Lighthouse-CI, schema validation y unicidad de contenido. |
| 11 | [`seo-competitive-benchmark`](seo-competitive-benchmark/SKILL.md) | ✅ MADURA | Investigación + Análisis + Estrategia | Analiza la carpeta del proyecto, deduce sector y ubicaciones, busca competidores orgánicos en 5 capas geográficas y extrae patrones accionables para superar a quien ya posiciona. |

---

## Flujo recomendado

```
Fase 1 · Investigación
  local-pack-multi-city
  serp-pattern-detector
  gbp-grid-extractor
  seo-competitive-benchmark  ← análisis completo desde la propia web del cliente

Fase 2 · Análisis profundo
  gbp-deep-profile
  web-pattern-extractor
  competitor-local-seo-audit

Fase 3 · Patrones
  local-seo-pattern-aggregator

Fase 4 · Blueprint
  web-blueprint-generator

Fase 5 · Generación
  landing-generator-servicio-barrio

Fase 6 · QA + Deploy
  landing-qa-runner
```

---

> Vuelve a este README cuando avancemos en el itinerario — las skills STUB irán pasando a MADURA clase a clase.

# Blueprint · ClimaTech Vallès
**Generado por:** web-blueprint-generator  
**Fecha:** 2026-05-18  
**Keyword analizada:** reparación de aire acondicionado  
**Hipótesis aplicadas:** H1, H4, H5, H7, H8, H9, H10

---

## Qué es este blueprint

El **plano de la web** antes de escribir una sola línea de código. Define:
- Qué páginas crear y con qué URLs
- Qué pone en cada página (headings, secciones, FAQ)
- Qué schema JSON-LD va en cada tipo de página
- Cómo se enlazan las páginas entre sí
- Qué presupuesto de rendimiento debe cumplir

---

## Estructura de archivos

```
blueprint/climatech-valles/
├── url-map.yaml              ← lista completa de URLs (31 páginas)
├── page-templates/
│   ├── home.md               ← plantilla página principal
│   ├── service-pillar.md     ← plantilla servicio madre
│   └── service-area.md       ← plantilla servicio × ciudad (★ la más importante)
├── schema-templates/
│   ├── home.jsonld           ← schema para la home
│   └── service-area.jsonld   ← schema para páginas de ciudad (HVACBusiness + FAQPage)
├── internal-linking.yaml     ← reglas de enlaces internos
├── lighthouse-budget.json    ← presupuesto de rendimiento
└── README.md                 ← este archivo
```

---

## Páginas a generar (31 total)

| Tipo | Nº | Ejemplo |
|------|----|---------|
| Global (home, contacto, etc.) | 7 | `/`, `/contacto/` |
| Servicio pillar | 4 | `/reparacion-aire-acondicionado/` |
| **Servicio × Ciudad** | **20** | `/reparacion-aire-acondicionado/sabadell/` |
| Blog (categorías) | — | Crece orgánicamente |
| **Total indexables** | **31** | |

---

## Las 5 decisiones de diseño más importantes

### 1. Una URL por servicio × ciudad — no por ciudad genérica
❌ Mal: `/sabadell/` (página ciudad genérica como hace Clic)  
✅ Bien: `/reparacion-aire-acondicionado/sabadell/` (página de intención exacta)

### 2. HVACBusiness + FAQPage schema en cada página de ciudad
El único competidor con schema correcto (A Tu Aire) rankea en 3 ciudades.  
Nadie en el mercado tiene FAQPage schema → ventaja inmediata.

### 3. Teléfono local por ciudad en header y schema
Un número diferente por ciudad, consistente entre GBP y web.  
Señal de NAP local que refuerza relevancia geográfica.

### 4. FAQ con 5-6 preguntas mínimas en cada página
Doble función: contenido útil para el usuario + FAQPage schema para rich results.  
Personalizar el nombre de la ciudad en las respuestas (no copypegar sin revisar).

### 5. Stack Astro → 0 JS por defecto
Los competidores tienen webs lentas (WordPress con plugins).  
Astro SSG genera HTML puro → rendimiento superior sin esfuerzo.

---

## Cómo adaptar este blueprint a un cliente real

1. Sustituir "ClimaTech Vallès" por el nombre real
2. Actualizar `url-map.yaml` con los servicios reales del cliente
3. Actualizar las ciudades con las zonas reales que quiere cubrir
4. Añadir los teléfonos locales reales en cada ciudad (H7)
5. Sustituir las variables `{{...}}` en los templates con los datos del cliente

---

## Siguiente paso

→ Ejecutar `landing-generator-servicio-barrio` con este blueprint como input  
→ Genera el código Astro real de las 20 páginas servicio × ciudad en modo dry-run primero

---

*YinyangSEO Academy · Clase 1 · Skill: web-blueprint-generator · 2026-05-18*

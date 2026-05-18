# Web Pattern Extractor · Informe
**Keyword:** reparación de aire acondicionado  
**Fecha:** 2026-05-18  
**Webs analizadas:** 4  
**Skill:** web-pattern-extractor (via Jina Reader)

---

## 1. Matriz comparativa

| Feature | Clic (Sabadell) | Clic (Terrassa) | HomeServe | A Tu Aire Sabadell |
|---------|:-:|:-:|:-:|:-:|
| **Title con ciudad** | ✅ | ✅ | ❌ | ✅ |
| **H1 con keyword+ciudad** | ⚠️ parcial | ✅ | ✅ | ✅ |
| **URL estructura ciudad** | `/sabadell/` | `/terrassa/` | `/aire-acondicionado` | `/servicio-ciudad` |
| **FAQ en página** | ✅ (6) | ✅ (6) | ✅ | ❌ |
| **Blog activo** | ✅ | ✅ | ✅ | ❌ |
| **Formulario lead** | ❌ | ✅ | ✅ | ❌ |
| **WhatsApp widget** | ✅ | ✅ | ❌ | ❌ |
| **NAP en footer** | ✅ | ✅ | ✅ | ✅ |
| **Teléfono en header** | ✅ | ✅ | ✅ | ✅ |
| **Bilingüe (es/ca)** | ❌ | ❌ | ❌ | ✅ |
| **Menú de servicios** | 9 páginas | 9 páginas | 15+ | 20+ |
| **Agencia SEO declarada** | ✅ | ✅ | — | ❌ |

---

## 2. Estructura de URLs detectada

### Clic Reparación — modelo "subdirectorio ciudad"
```
clicreparacion.com/
├── sabadell/          ← página ciudad
├── terrassa/
├── barcelona/
├── madrid/
├── mataro/
├── valencia/
├── sevilla/
├── alicante/
├── reparacion-aire-acondicionado/    ← servicio global
├── reparacion-caldera/
├── instalacion-aire-acondicionado/
├── mantenimiento-aire-acondicionado/
├── reparacion-electrodomesticos/
└── blog/
```
**Patrón:** city hubs + service pages globales. Las páginas de ciudad actúan como landing page que enlaza a los servicios.

### A Tu Aire Sabadell — modelo "keyword+ciudad"
```
atuairesabadell.com/
├── aire-acondicionado-split-sabadell
├── aerotermia-sabadell
├── bomba-calor-sabadell
├── calderas-gas-sabadell
├── sistemas-vrv-sabadell
├── fan-coils-sabadell
└── frio-industrial-sabadell
```
**Patrón:** una URL por servicio específico + ciudad. Muy granular. Explica por qué rankea en múltiples búsquedas.

---

## 3. Patrones de contenido comunes en los que rankean

| Sección | Clic | HomeServe | A Tu Aire |
|---------|:----:|:---------:|:---------:|
| Hero con tagline + CTA | ✅ | ✅ | ✅ |
| Grid de servicios (iconos) | ✅ | ✅ | ✅ |
| Proceso en 3 pasos | ✅ | — | — |
| Bloque de confianza (certificados/años) | ✅ | ✅ | ✅ |
| FAQ | ✅ | ✅ | ❌ |
| Blog/noticias | ✅ | ✅ | ❌ |
| NAP completo + mapa | ✅ | ✅ | ✅ |
| Cómo llegar (Google Maps links) | ✅ | — | — |

---

## 4. Hallazgos destacados

### 🔴 Clic Reparación tiene errores de template graves
- Página Sabadell: la FAQ menciona **"Valencia"** y **"Alicante"** en lugar de Sabadell — copy-paste sin revisar
- Página Terrassa: "Terrasssa" (triple s) en 2 respuestas del FAQ
- A pesar de estos errores, rankea #1 en Local Pack → **Google no penaliza estos fallos de contenido para Local Pack**

### 🟡 Clic es un directorio/intermediario, no un servicio directo
- Su modelo de negocio es **conectar usuarios con técnicos** (como Habitissimo pero sin marca conocida)
- No tienen técnicos propios — son un marketplace local
- Esto explica el "servicio gratuito para el usuario" en el FAQ
- Construido y gestionado por **Seo Local Barcelona** (agencia)
- Expansión activa: 8+ ciudades en footer

### 🟢 A Tu Aire: el especialista técnico que rankea gracias a granularidad de URLs
- 20+ páginas de servicio × ciudad con keywords exactas en la URL
- Bilingüe español/catalán — captura búsquedas en ambos idiomas
- Sin FAQ ni blog → debilidad estructural
- Especialización industrial (VRV, cassettes, fan coils) = diferenciador único
- Rankea en 3 ciudades (Sabadell, Terrassa, Barcelona) con un dominio local — gracias a la arquitectura de URLs, no a las fichas GBP

### 🔵 HomeServe: autoridad nacional, no se puede superar en DA/backlinks
- Modelo: packs de reparación (suscripción) + reparaciones puntuales
- No compite en Local Pack — compite en orgánico con autoridad de dominio
- Formulario de captación very above the fold — estrategia de lead gen pura
- No es un competidor real para un negocio local en Local Pack

---

## 5. N-gramas más frecuentes detectados

| N-grama | Aparece en |
|---------|-----------|
| aire acondicionado | todas |
| reparación + ciudad | todas |
| técnico + ciudad | 3/4 |
| servicio técnico | 3/4 |
| instalación + aire acondicionado | 3/4 |
| mantenimiento | 3/4 |
| a domicilio | 2/4 |
| urgente / urgencia | 2/4 |
| garantía | 2/4 |
| todas las marcas | 2/4 |

---

## 6. Hipótesis generadas

| # | Hipótesis | Confianza | Input para |
|---|-----------|:---------:|-----------|
| H5 | URLs con patrón `/servicio-ciudad` rankean en múltiples ciudades sin necesidad de fichas GBP adicionales | ALTA | blueprint |
| H6 | FAQ en página es estándar en los que rankean — su ausencia es una debilidad | ALTA | blueprint |
| H7 | El bilingüismo es/ca captura búsquedas extra en Cataluña sin esfuerzo adicional | MEDIA | blueprint |
| H8 | Un directorio/intermediario puede dominar el Local Pack con template + SEO agency sin tener técnicos propios | ALTA | estrategia |
| H9 | Los errores de template no afectan al Local Pack — afectan a la conversión | MEDIA | QA checklist |
| H10 | La especialización industrial (VRV, fan coils) es un diferenciador que nadie más explota en estas ciudades | MEDIA | blueprint |

---

## 7. Próximos pasos

→ **`competitor-local-seo-audit`** sobre clicreparacion.com (auditoría profunda: backlinks, schema, Core Web Vitals)  
→ **`local-seo-pattern-aggregator`** con todos los datos de Fase 1 + 2 para priorizar hipótesis  
→ **`web-blueprint-generator`** con las hipótesis H1–H10 como input

---

*Generado por skill `web-pattern-extractor` (via Jina Reader) · YinyangSEO Academy · 2026-05-18*

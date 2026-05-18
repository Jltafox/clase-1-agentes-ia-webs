# Hipótesis priorizadas · reparación de aire acondicionado × 5 ciudades
**Fecha:** 2026-05-18  
**Grupo A (ganadores):** 5 negocios en posición #1 del Local Pack  
**Grupo B (resto):** 10 negocios en posiciones #2-#3  
**Fuentes:** local-pack-multi-city + gbp-deep-profile + web-pattern-extractor + competitor-local-seo-audit

> ⚠️ **Aviso estadístico:** muestra pequeña (n=15 negocios). Las diferencias de proporción son orientativas. Tratar como hipótesis de trabajo, no como verdades absolutas.

---

## Hipótesis por orden de prioridad

### H1 [HIGH · easy] Posts mensuales en GBP es el diferenciador #1
**Dato:** 60% del Grupo A publica posts mensuales en GBP. Solo 10% del Grupo B.  
**Diferencia:** +50 pp — la señal más fuerte del dataset.  
**Interpretación:** Google recompensa la actividad reciente en la ficha. Un post al mes parece suficiente.  
**Acción:** publicar mínimo 1 post/mes en cada ficha GBP. CTA: "Llamar ahora" + teléfono local.  
**Modelo:** Clic Reparación — mismo contenido replicado en todas las fichas el mismo día.

---

### H2 [HIGH · disruptiva] Local Pack NO requiere una web de calidad
**Dato:** 60% del Grupo A tiene web accesible. 90% del Grupo B tiene web accesible.  
**Diferencia:** -30 pp (los ganadores tienen *menos* web funcional, no más).  
**Interpretación:** Climagisa (#1 Barcelona, 4.9★) y NOVAMYR (#1 Madrid, 5.0★) no tienen web funcional. Ganan el Local Pack solo con la ficha GBP.  
**Conclusión:** para Local Pack, **la ficha GBP importa más que la web**. La web es crítica para orgánico, no para el map pack.  
**Implicación en blueprint:** priorizar GBP antes que la web. La web se optimiza para capturar el tráfico que viene del orgánico.

---

### H3 [HIGH · easy] Blog activo correlaciona con dominancia multi-canal
**Dato:** 40% del Grupo A tiene blog activo. Solo 10% del Grupo B.  
**Diferencia:** +30 pp.  
**Interpretación:** los negocios que tienen blog no solo rankean en Local Pack — también aparecen en orgánico en múltiples ciudades.  
**Acción:** 1-2 artículos/mes con keywords long-tail (ej. "cuánto cuesta reparar aire acondicionado", "averías más comunes AA").  
**Coste:** bajo. Puede generarse con IA + revisión humana.

---

### H4 [HIGH · easy] FAQ en página de ciudad es estándar en los que rankean
**Dato:** 40% del Grupo A tiene FAQ on-page. 20% del Grupo B.  
**Diferencia:** +20 pp.  
**Hallazgo adicional:** nadie tiene **FAQPage schema** implementado (0% en ambos grupos).  
**Acción doble:** añadir FAQ con 5-6 preguntas + implementar `FAQPage` JSON-LD → diferenciación total frente a todos los competidores detectados.  
**Nivel de esfuerzo:** bajo (2-3 horas de implementación).

---

### H5 [HIGH · easy] 20+ fotos en GBP es una oportunidad abierta para todos
**Dato:** 0% del Grupo A y 0% del Grupo B supera las 10 fotos en GBP.  
**Clic Reparación tiene 3-4 fotos por ficha** en todas sus ubicaciones.  
**Interpretación:** nadie en este mercado trabaja las imágenes GBP. Subir 20-30 fotos reales (instalaciones, equipo, trabajos) es una ventaja inmediata que nadie ha explotado.  
**Acción:** fotografiar una intervención real → subir a GBP clasificadas (interior, equipo, trabajo, producto).

---

### H6 [MEDIUM · easy] Número de reseñas no es el factor crítico
**Dato:** el umbral para ser #1 es sorprendentemente bajo:
- Clic Reparación Sabadell: #1 con solo **11 reseñas**
- NOVAMYR Madrid: #1 con **28 reseñas**
- RM CLIMATIZACIÓN Barcelona: 268 reseñas → posición #2

**Interpretación:** la relevancia geográfica y la actividad de la ficha (posts, fotos, respuestas) pesan más que el volumen de reseñas.  
**Acción:** no bloquearse en "necesito 100 reseñas antes de rankear". Con 15-20 reseñas bien gestionadas se puede competir por el #1.

---

### H7 [MEDIUM · easy] Teléfono local dedicado por ciudad como señal de relevancia
**Observación:** Clic Reparación usa un teléfono físico diferente para cada ciudad:
- Sabadell: 936 94 06 82
- Terrassa: 936 94 03 96
- Rubí: 936 94 07 84

**Hipótesis:** Google puede usar la consistencia NAP (Nombre + Dirección + Teléfono) entre GBP y web para validar la relevancia local.  
**Acción:** si se abre una ficha GBP en una nueva ciudad, usar un número local (puede ser un desvío) consistente entre GBP y la página /ciudad/ de la web.

---

### H8 [MEDIUM · medium] Arquitectura URL /servicio-ciudad permite rankear en múltiples ciudades desde un solo dominio
**Dato:** atuairesabadell.com aparece en orgánico en 3/5 ciudades con dominio de Sabadell.  
**Patrón:** URLs tipo `/aerotermia-sabadell`, `/calderas-gas-sabadell` → 376 páginas en sitemap.  
**Acción:** crear páginas individuales por servicio × ciudad (ej. `/reparacion-aire-acondicionado-terrassa/`).  
**Impacto:** captura tráfico long-tail sin necesidad de fichas GBP en cada ciudad.

---

### H9 [MEDIUM · easy] HVACBusiness schema es el único tipo correcto para este sector
**Dato:** solo A Tu Aire usa HVACBusiness schema. El líder del Local Pack (Clic) no tiene LocalBusiness de ningún tipo.  
**Interpretación:** schema no es crítico para Local Pack, pero sí para la comprensión semántica del negocio por parte de Google.  
**Acción:** implementar `HVACBusiness` (subtipo de LocalBusiness) con `openingHoursSpecification`, `areaServed`, `telephone`, `address`.

---

### H10 [LOW · easy] Bilingüismo es/ca captura un segmento sin competencia
**Observación:** solo atuairesabadell.com tiene versión en catalán.  
**Potencial:** búsquedas en catalán ("reparació aire condicionat Sabadell") tienen menos competencia y similar volumen en el área.  
**Acción:** añadir versión en catalán de las páginas principales con `hreflang` correcto.  
**Coste:** bajo si se usa IA para traducción + revisión nativa.

---

## Matriz de priorización

| # | Hipótesis | Impacto Local Pack | Impacto Orgánico | Esfuerzo | Prioridad |
|---|-----------|:-:|:-:|:-:|:-:|
| H1 | Posts mensuales GBP | 🔴 MUY ALTO | 🟡 MEDIO | 🟢 BAJO | ⭐⭐⭐⭐⭐ |
| H5 | 20+ fotos GBP | 🔴 ALTO | ❌ | 🟢 BAJO | ⭐⭐⭐⭐⭐ |
| H4 | FAQ + FAQPage schema | 🟡 MEDIO | 🔴 ALTO | 🟢 BAJO | ⭐⭐⭐⭐⭐ |
| H2 | GBP > web (mindset) | 🔴 ALTO | ❌ | 🟢 BAJO | ⭐⭐⭐⭐ |
| H7 | Teléfono local por ciudad | 🔴 ALTO | 🟡 MEDIO | 🟢 BAJO | ⭐⭐⭐⭐ |
| H9 | HVACBusiness schema | 🟡 MEDIO | 🔴 ALTO | 🟢 BAJO | ⭐⭐⭐⭐ |
| H8 | URLs /servicio-ciudad | ❌ | 🔴 ALTO | 🟡 MEDIO | ⭐⭐⭐ |
| H3 | Blog activo | 🟡 MEDIO | 🔴 ALTO | 🟡 MEDIO | ⭐⭐⭐ |
| H6 | No bloquearse en reseñas | mindset | mindset | — | ⭐⭐⭐ |
| H10 | Bilingüismo es/ca | 🟡 MEDIO | 🟡 MEDIO | 🟢 BAJO | ⭐⭐ |

---

*Las hipótesis HIGH + easy (H1, H4, H5, H7, H9) son el input directo para `web-blueprint-generator`.*

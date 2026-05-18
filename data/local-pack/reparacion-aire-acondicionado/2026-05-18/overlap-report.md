# Overlap Report · reparación de aire acondicionado
**Fecha:** 2026-05-18  
**Ciudades:** Sabadell, Terrassa, Barcelona, Madrid Centro, Valencia  
**Skill:** local-pack-multi-city

---

## 1. Local Pack · Negocios únicos detectados (15)

> ⚠️ Ningún negocio aparece en más de 1 ciudad. Mercado altamente fragmentado y local.
> Señal: no hay cadenas ni operadores multi-ciudad dominando el Local Pack en esta keyword.

| Ciudad | #1 Local Pack | #2 Local Pack | #3 Local Pack |
|--------|--------------|--------------|--------------|
| Sabadell | Clic Reparación ⭐5.0 (11) | Clima BCN ⭐5.0 (8) | AIR-CONFORT VALLÈS ⭐4.5 (32) |
| Terrassa | Clic Reparación Terrassa ⭐4.8 (45) | APFCLIMA ⭐5.0 (65) | Tecno clima ⭐4.8 (26) |
| Barcelona | Climagisa ⭐4.9 (35) | RM CLIMATIZACIÓN ⭐4.9 (268) | Reparacion Aire Acondicionado ⭐4.8 (45) |
| Madrid Centro | NOVAMYR ⭐5.0 (28) | REPARACIÓN E INSTALACIÓN AA ⭐4.8 (20) | SAT IberiaClima ⭐5.0 (3) |
| Valencia | Clima Solution ⭐4.8 (137) | Aire Acondicionado Proman ⭐5.0 (6) | Aire Clim ⭐4.8 (172) |

### 🔎 Patrón de marca: Clic Reparación
- **Clic Reparación** → #1 en Sabadell
- **Clic Reparación Terrassa** → #1 en Terrassa

Misma marca, dos fichas GBP distintas. Posible cadena local que replica el modelo por ciudad.
Candidato prioritario para analizar con `gbp-deep-profile`.

---

## 2. Orgánico · Dominios en múltiples ciudades

| Dominio | Ciudades (de 5) | Tipo |
|---------|:-:|------|
| es.wallapop.com | 5/5 | Marketplace — no compite realmente |
| habitissimo.es | 4/5 | Directorio de servicios |
| homeserve.es | 4/5 | Empresa de mantenimiento del hogar |
| atuairesabadell.com | 3/5 | ⚠️ Web local de Sabadell posicionando fuera de su ciudad |
| radiadorssoler.com | 2/5 | Web local |
| airmant.com | 2/5 | Web local |
| empresaclimatizacion.com | 2/5 | Web local |
| aireacondicionadogisbert.com | 2/5 | Web local |
| aire-acondicionado.barcelona | 2/5 | Web local Barcelona |
| milanuncios.com | 2/5 | Clasificados |

### 🔎 Observaciones orgánico

1. **Wallapop y Habitissimo dominan transversalmente** → no son competencia real pero ocupan posiciones valiosas.
2. **HomeServe (4/5 ciudades)** → empresa nacional con web optimizada. Competidor real a nivel SEO.
3. **atuairesabadell.com (3/5)** → web local de Sabadell que aparece en 3 ciudades. Caso de estudio interesante: ¿cómo lo consigue? Candidato para `web-pattern-extractor`.
4. **Mercado local poco consolidado** → oportunidad para una web bien estructurada que cubra múltiples ciudades.

---

## 3. Hipótesis preliminares

| # | Hipótesis | Señal | Siguiente paso |
|---|-----------|-------|----------------|
| H1 | Una web con páginas por ciudad puede posicionarse en varias SERPs locales | atuairesabadell.com en 3/5 ciudades | `web-pattern-extractor` |
| H2 | El modelo "misma marca, ficha GBP por ciudad" funciona para Local Pack | Clic Reparación en Sabadell + Terrassa | `gbp-deep-profile` |
| H3 | HomeServe es el competidor SEO nacional más sólido | 4/5 ciudades orgánico | `competitor-local-seo-audit` |
| H4 | Ratings altos (≥4.8) son la norma en Local Pack — no es diferenciador | 14/15 negocios ≥4.8 | — |

---

## 4. Próximos pasos recomendados

1. **`gbp-deep-profile`** → analizar Clic Reparación (Sabadell + Terrassa) y RM CLIMATIZACIÓN (268 reseñas).
2. **`web-pattern-extractor`** → auditar atuairesabadell.com y homeserve.es como casos opuestos (local vs nacional).
3. **`competitor-local-seo-audit`** → auditoría completa de HomeServe para entender su estrategia multi-ciudad.

---

*Generado por skill `local-pack-multi-city` · YinyangSEO Academy*

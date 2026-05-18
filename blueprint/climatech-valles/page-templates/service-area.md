# Plantilla: Servicio × Ciudad
# Tipo de página más importante del sitio (H8)
# Variables: {{servicio}}, {{ciudad}}, {{telefono}}, {{cp}}, {{lat}}, {{lng}}

---
## METADATOS SEO

**Title:**
`{{servicio_titulo}} en {{ciudad}} | ClimaTech Vallès`
Ejemplo: `Reparación de Aire Acondicionado en Sabadell | ClimaTech Vallès`
Máx. 60 caracteres.

**Meta description:**
`Técnico de {{servicio}} en {{ciudad}} · Disponible hoy · Presupuesto sin compromiso · Llama al {{telefono}}`
Máx. 155 caracteres.

**Canonical:** `https://climateachvalles.com/{{servicio-slug}}/{{ciudad-slug}}/`

**hreflang:** (H10)
```html
<link rel="alternate" hreflang="es" href="/{{servicio-slug}}/{{ciudad-slug}}/" />
<link rel="alternate" hreflang="ca" href="/ca/{{servicio-slug}}/{{ciudad-slug}}/" />
```

---
## ESTRUCTURA DE HEADINGS

**H1:** `{{servicio_titulo}} en {{ciudad}}`
→ Debe contener keyword exacta + ciudad. Sin emojis ni florituras.

**H2 (secciones obligatorias — en este orden):**
1. `¿Qué incluye nuestro servicio de {{servicio}} en {{ciudad}}?`
2. `¿Cuánto cuesta {{servicio_lower}} en {{ciudad}}?`
3. `¿Por qué elegirnos en {{ciudad}}?`
4. `Preguntas frecuentes sobre {{servicio}} en {{ciudad}}` ← H4: FAQ obligatoria
5. `Zonas próximas que también cubrimos`

---
## SECCIONES OBLIGATORIAS

### HERO (primera pantalla, mobile-first)
- H1 visible sin scroll
- Teléfono {{telefono}} en botón sticky (CTA primario) — H1 hipótesis
- Texto: "Técnico disponible hoy en {{ciudad}}"
- Sin imagen hero pesada (LCP < 2.5s)

### SERVICIOS INCLUIDOS
- Lista de 6-8 puntos con lo que incluye el servicio
- Marcas que se trabajan (Samsung, Daikin, Mitsubishi, etc.)
- Urgencias / mismo día si aplica

### PRECIO / PRESUPUESTO
- Tabla con rangos orientativos (captura long-tail "precio reparación AC {{ciudad}}")
- CTA: "Pide presupuesto sin compromiso"
- Nota: precio final siempre tras diagnóstico

### TRUST SIGNALS
- Años de experiencia
- Nº de reparaciones realizadas (si disponible)
- Garantía en cada reparación
- Certificaciones técnicas

### FAQ (obligatoria — H4) — mínimo 5 preguntas
```
1. ¿En cuánto tiempo llega el técnico a {{ciudad}}?
2. ¿Cuánto cuesta la visita de diagnóstico en {{ciudad}}?
3. ¿Qué marcas de aire acondicionado reparan en {{ciudad}}?
4. ¿Ofrecen garantía en las reparaciones en {{ciudad}}?
5. ¿Hacen presupuesto sin compromiso en {{ciudad}}?
6. ¿Trabajan en fines de semana en {{ciudad}}?
```
→ Todas las respuestas deben mencionar {{ciudad}} al menos una vez.

### ZONAS PRÓXIMAS (internal linking — H8)
Lista de ciudades vecinas enlazadas a su página /servicio/ciudad-vecina/
Ejemplo desde Sabadell: Terrassa · Rubí · Cerdanyola · Sant Cugat

### NAP FOOTER (obligatorio en todas las páginas)
```
ClimaTech Vallès — {{ciudad}}
Teléfono: {{telefono}}
Horario: Lun–Vie 8:00–20:00 · Sáb 9:00–17:00
```

---
## LONGITUD DE CONTENIDO
- Mínimo: 600 palabras visibles
- Recomendado: 900-1200 palabras (basado en competidores que rankean)
- El FAQ cuenta como contenido

---
## NOTAS DE PRODUCCIÓN
- Mismo template para todas las ciudades — solo cambian las variables
- El teléfono debe ser el número LOCAL de esa ciudad (H7)
- FAQ: personalizar al menos las respuestas con el nombre de la ciudad
- NO copiar/pegar sin revisar variables — error de Clic Reparación a evitar

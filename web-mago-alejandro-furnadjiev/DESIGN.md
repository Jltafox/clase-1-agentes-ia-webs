# DESIGN.md — Sistema de diseño

> Sistema canónico del proyecto: tokens, lenguaje visual y patrones aprobados.
> **Nota técnica**: los agentes no cargan este archivo automáticamente — está referenciado desde `AGENTS.md`.
> Estado: **BORRADOR v0** — pendiente de validar con el cliente y con las fotos/vídeos reales.

## Dirección visual

Elegancia de teatro clásico con un giro contemporáneo: **oscuro, dorado, mucho aire**. La web debe transmitir "mago premiado de verdad" — magia de cerca premium para público adulto (empresas y celebraciones privadas). Nada de imaginería infantil ni de "animación de fiestas".

## Tokens base

*(Fundacionales: cambiarlos exige justificación en `memory/feedback_diseno_*.md`.)*

### Color

| Token | Valor propuesto | Uso |
|-------|-----------------|-----|
| `--bg` | `#101014` | Fondo principal (casi negro, cálido) |
| `--bg-raised` | `#1a1a21` | Tarjetas, superficies elevadas |
| `--text` | `#f2efe9` | Texto principal (blanco roto) |
| `--muted` | `#a39e93` | Texto secundario |
| `--accent` | `#c9a227` | Dorado — CTAs, detalles, separadores |
| `--accent-hover` | `#e0b93e` | Hover del acento |
| `--border` | `#2c2c35` | Bordes sutiles |

### Tipografía

- **Titulares**: serif con carácter (propuesta: *Fraunces* o *Playfair Display*), pesos 500/700.
- **Cuerpo**: sans humanista legible (propuesta: *Inter* o *Source Sans 3*), pesos 400/600.
- Escala: 1.25 (major third). Base 16px móvil / 18px desktop.

### Espaciado y radios

- Escala de espaciado: 4 / 8 / 16 / 24 / 40 / 64 / 96 px.
- Border-radius canónicos: `4px` (chips), `12px` (tarjetas), `999px` (botones pill).

## Lenguaje visual

- Separadores finos dorados (1px, opacidad 40%) entre secciones.
- Botón primario: pill dorado sobre fondo oscuro, texto oscuro. Un solo CTA primario por pantalla: **"Pide presupuesto"**.
- CTA secundario recurrente: WhatsApp (icono + texto, estilo outline).
- Tarjetas de servicio: fondo `--bg-raised`, borde sutil, sin sombras duras.
- Fotos: protagonistas, a sangre o con radio 12px. Placeholders mientras no haya material: ratio 3:2 (horizontales) y 4:5 (retratos), fondo `--bg-raised` con icono ✦.

## Componentes y patrones

- **Hero**: titular grande + subtítulo + CTA + (futuro) vídeo/foto de actuación.
- **Bloque credenciales**: fila de premios (Almería 1999, FLASOMA 2004, Memorial Ascanio 2006) — sobrio, tipo "press bar".
- **Testimonios**: cita + nombre + tipo de evento. *Solo reales, nunca inventados.*
- **FAQ** por servicio (acordeón accesible, `<details>`).

## Responsive

- Breakpoints: móvil ≤ 720px · desktop > 720px.
- Tap targets mínimos 44×44px. Hover solo en desktop (nada "nervioso").
- Titulares: reducir un paso de escala en móvil.

## Lo que NO funciona

*(Se irá llenando con decisiones validadas como fallidas.)*

- Clichés de mago genérico: chisteras con conejos, varitas con estrellas, cortinas rojas de clipart.
- **2026-07-06** — Variante clara "infantil" eliminada del sistema: la magia infantil queda fuera del alcance del proyecto. Un solo tema visual (oscuro elegante) para toda la web.

## Cuándo este archivo miente

Si el código contradice este documento: manda el código, avisa al usuario y actualiza la doc en el mismo commit.

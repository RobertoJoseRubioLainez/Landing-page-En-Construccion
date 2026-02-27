# Resonanza — Landing Page "En Construcción"

Página estática de próximo lanzamiento para **Resonanza**, desplegada en [resonanza.com](https://resonanza.com).

---

## Vista general

Diseño split-screen elegante y oscuro:

- **Izquierda** — Imagen del violín con overlay metálico
- **Derecha** — Logo, animación generativa, textos en plata y formulario de lista de espera

---

## Stack

| Elemento | Tecnología |
|----------|-----------|
| Estructura | HTML5 (un solo archivo autocontenido) |
| Estilos | CSS3 embebido — paleta exclusiva en plata metálica |
| Animación | [p5.js 1.9.4](https://p5js.org/) — noise-based generative art |
| Formulario | [Formspree](https://formspree.io/) — AJAX sin recarga |
| Tipografía | [Inter](https://fonts.google.com/specimen/Inter) — Google Fonts |
| Deploy | [Vercel](https://vercel.com/) |

---

## Características

- **Animación generativa** — 3 capas de líneas con ruido Perlin en paleta plateada (`#8A8A8A`, `#C0C0C0`, `#E8E8E8`) con `blendMode(ADD)` para efecto de brillo metálico
- **Glassmorphism** — Tarjeta de formulario con `backdrop-filter: blur` y borde plateado sutil
- **Formulario de waitlist** — Campos: nombre, correo y "¿Tocas el violín?". Envío AJAX a Formspree
- **Responsive** — Adaptado a mobile (375px) y desktop (1440px)
- **Optimizado** — Animación se pausa automáticamente cuando la pestaña no está activa

---

## Archivos

```
├── index.html              # Página completa (HTML + CSS + JS embebidos)
├── vercel.json             # Configuración de deploy estático
├── logo Resonanza 500x500 T.png
└── Fondo Resonanza.jpg
```

---

## Deploy

El sitio se despliega automáticamente en Vercel desde este repositorio.

**URL de producción:** [https://resonanza.com](https://resonanza.com)

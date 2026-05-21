# Portafolio Web — Leidydith Ruiz

Sitio web de portafolio personal para Leidydith Ruiz, diseñadora gráfica y visual. Desarrollado con HTML y CSS puro, sin dependencias externas ni frameworks.

## Descripción

Página de una sola vista (single-page) con navegación por anclas que presenta el perfil profesional, proyectos seleccionados y un formulario de contacto.

## Estructura del proyecto

```
Portafolio-Web/
├── index.html        # Página principal (único archivo fuente)
├── Notas.txt         # Notas de desarrollo
└── README.md         # Este archivo
```

## Secciones

| Sección | ID | Descripción |
|---|---|---|
| Navegación | — | Barra fija con desplazamiento suave |
| Hero | `#hero` | Presentación principal con foto y llamada a la acción |
| Sobre mí | `#sobre-mi` | Biografía, habilidades y estadísticas |
| Proyectos | `#proyectos` | 3 tarjetas de trabajos seleccionados |
| Contacto | `#contacto` | Datos de contacto y formulario mailto |
| Footer | — | Derechos y enlaces a redes sociales |

## Tecnologías

- **HTML5** semántico (`<nav>`, `<section>`, `<article>`, `<aside>`, `<header>`, `<footer>`)
- **CSS3** con variables personalizadas (`--negro`, `--acento`, `--gris`, etc.)
- **Google Fonts** — Playfair Display (títulos) + Inter (cuerpo)
- **Flexbox** para maquetación de secciones y tarjetas
- **Responsive design** con media queries en 900 px y 600 px

## Paleta de colores

| Variable | Valor | Uso |
|---|---|---|
| `--negro` | `#1e2d0a` | Fondo principal |
| `--blanco` | `#f5f5f5` | Texto general |
| `--acento` | `#E63946` | Botones, etiquetas y detalles |
| `--gris` | `#2a3f10` | Fondo de secciones alternas |
| `--gris-claro` | `#3a5518` | Bordes y separadores |

## Mejoras pendientes

1. **Menú hamburguesa en móvil** — el menú se oculta en pantallas ≤ 600 px; requiere JavaScript o el truco CSS de `<input type="checkbox">`.
2. **Imágenes reales** — reemplazar los placeholders del hero y las tarjetas por fotos reales optimizadas en formato WebP (≤ 200 KB cada una).
3. **Animaciones de entrada** — usar `@keyframes` o `animation-timeline: scroll()` para animar elementos al hacer scroll.

## Accesibilidad

- Atributos `aria-label` en navegación, hero, tarjetas y formulario.
- Roles semánticos: `role="list"` y `role="listitem"` en habilidades.
- Revisión de accesibilidad completada: 2026-05-21.

## Repositorio

**GitHub:** [informacion-glitch/Portafolio-Web](https://github.com/informacion-glitch/Portafolio-Web)

---

*Proyecto desarrollado con Claude Code — Anthropic*

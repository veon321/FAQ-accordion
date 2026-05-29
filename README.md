# Frontend Mentor - FAQ accordion solution

This is a clean, responsive, and modern solution to the FAQ accordion challenge on Frontend Mentor.

## Links

- Solution URL: [https://github.com/veon321/FAQ-accordion](https://github.com/veon321/FAQ-accordion)
- Live Site URL: [https://veon321.github.io/FAQ-accordion/](https://veon321.github.io/FAQ-accordion/)

## Built with

- **Semantic HTML5 markup**: Built using native disclosure widgets (`<details>` and `<summary>`) to achieve fully accessible, interactive accordion states without relying on JavaScript.
- **CSS Custom Properties (Variables)**: Used for precise implementation of the active design system, controlling typography metrics and fiolet thematic color tokens.
- **Flexbox Layout**: Employed within component structures to guarantee perfect directional item positioning and symmetrical asset spacing.
- **Modern CSS Math Functions (`clamp()`)**: Applied to global paddings and heading text sizes to drive completely fluid layout distribution across varying screen widths.

## Features

- **Native Interactive State Handling**: Leverages built-in browser engine logic via `<details>` blocks to switch disclosure states seamlessly, achieving native keyboard navigation and superior screen-reader compatibility right out of the box.
- **Dynamic CSS Icon Toggling**: Eliminates redundant DOM elements by monitoring the active `[open]` element state directly in CSS, automatically hot-swapping asset profiles between the plus and minus icons.
- **Fluid Element Scaling**: Replaces static, hardcoded breakpoints with mathematical scaling expressions (`clamp()`), forcing text blocks and container gaps to scale continuously across the full mobile-to-desktop viewport continuum.
- **Two-Tier Seamless Vector Backgrounds**: Utilizes dynamic background layout positioning (`background-size: 100% auto`) combined with responsive design tokens to scale vectors perfectly across the horizontal plain while preserving the precise vertical design aspect ratio.

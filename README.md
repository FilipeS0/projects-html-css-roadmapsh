# Tooltip UI

## Project Goal

The goal of this small project is to build an elegant, accessible tooltip component that appears above navigation items using only HTML and CSS. You'll practice CSS positioning, hover/focus effects, transitions, and simple animation techniques (fade, slide, scale) without JavaScript. By the end you'll understand how to create interactive UI affordances with purely declarative markup and styles.

## Features

-   Pure HTML & CSS implementation — no JavaScript required.
-   Tooltips positioned above navigation items with a small "triangle" pointer.
-   Smooth transitions and optional animation styles: fade-in, slide-up, scale-in.
-   Hover and focus states to support keyboard users.
-   Small, easy-to-customize CSS surface: colors, timing, spacing, and pointer placement.

## Quick Start

1. Clone or download the repository.
2. Open the demo in a browser by opening [index.html](index.html).

## Exercise Notes

-   Structure: a semantic `nav` containing a `ul` of `li` items. Each `li` holds the visible link and a sibling tooltip element.
-   Positioning: tooltips are absolutely positioned relative to the `li` (or a positioned container) and placed above the item using `bottom` or `transform` offsets.
-   Pointer: the small diamond/triangle is created by rotating a square or using pseudo-elements and positioned to align with its parent link.
-   Transitions/animations: implement a base fade using `opacity` + `visibility` and add optional transforms for slide (`translateY`) or scale (`transform: scale()`), toggled on `:hover` and `:focus-within`.
-   Keyboard: include focus styles and make the tooltip visible on `:focus-within` so keyboard users see the tooltip when tabbing to links.
-   Customization: change tooltip color, radius, spacing, and animation timing in the CSS variables or class rules.

## Project Structure

```
accessible-form-ui/
├── index.html          # Demo page showcasing the accessible form UI
├── README.md           # This file
├── LICENSE             # MIT License
└── assets/
    └── style.css       # Component styles
```

## See the result and the goal

-   The project goal: [roadmap project](https://roadmap.sh/projects/tooltip-ui)
-   Live demo: [filipes0.github.io/tooltip-ui](https://filipes0.github.io/tooltip-ui)

## Author

-   **LinkedIn:** https://linkedin.com/in/FilipeS0
-   **GitHub:** https://github.com/FilipeS0

## License

This project is available under the MIT License. See the [LICENSE](LICENSE) file for details.

## Feedback

Contributions, suggestions, and PRs are welcome — please open an issue or submit a PR with improvements.

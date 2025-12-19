# Accessible Form UI

## Project Goal

Build a static, accessible form UI using only HTML and CSS. The UI includes fields for full name, email, password, and confirm password, a control to toggle password visibility, a visual profile completeness indicator, and a checklist of requirements that show how the form reaches 100% completeness. The component is intentionally static (no JavaScript) so it can be enhanced later.

## Features

-   Static HTML/CSS implementation of a form UI
-   Accessible labels connected with `for` attributes
-   Focus-visible styles for keyboard users
-   Space reserved for inline error messages and ARIA attributes
-   Password visibility control (UI only)
-   Profile completeness visual and checklist

## Quick Start

1. Clone or download the repository.
2. Open the demo in a browser by opening [index.html](index.html).

## Exercise Notes

This exercise focuses on structure and accessibility rather than runtime validation. Implement the layout and visual behaviors using only HTML and CSS. Later you can add JavaScript to:

-   Toggle password visibility interactively
-   Validate inputs and display appropriate error messages
-   Update the completeness indicator and checklist dynamically

## Accessibility Guidelines

Follow these guidelines while building the UI:

-   Labeling: Ensure every form control has an associated `<label>` with a matching `for` attribute.
-   Focus State: Provide a clear, visible focus style for keyboard navigation (`:focus` / `:focus-visible`).
-   Error Messaging: Reserve space near inputs for inline error messages; associate them with inputs using ARIA when needed.
-   ARIA Attributes: Use `aria-required` on required fields and `aria-invalid` when showing errors.
-   Color Contrast: Ensure text/background contrast meets WCAG recommendations.
-   Interactive Elements: Make the password visibility toggle keyboard-accessible and announce its state to assistive technologies.

Test with screen readers and accessibility tools such as Axe or Lighthouse and iterate as needed.

## Project Structure

```
accessible-form-ui/
├── index.html          # Demo page showcasing the accessible form UI
├── README.md           # This file
├── LICENSE             # MIT License
└── assets/
    └── style.css       # Component styles
```

## SEO / Meta

This demo includes basic SEO/meta tags for description, keywords, canonical URL, and Open Graph/Twitter card metadata. These tags are present in the document head of [index.html](index.html).

## See the result and the goal

-   The project goal: https://roadmap.sh/projects/accessible-form-ui
-   Live demo: https://filipes0.github.io/accessible-form-ui

## Author

-   **LinkedIn:** https://linkedin.com/in/FilipeS0
-   **GitHub:** https://github.com/FilipeS0

## License

This project is available under the MIT License. See the [LICENSE](LICENSE) file for details.

## Feedback

Contributions, suggestions, and PRs are welcome — please open an issue or submit a PR with improvements.

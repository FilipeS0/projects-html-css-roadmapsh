# Image Grid

## Project Goal

Create a responsive image grid layout using CSS Grid to practice advanced CSS layout techniques. The project demonstrates how to arrange multiple images in a flexible grid pattern that adapts to different screen sizes while maintaining a visually appealing design.

## Features

-   **CSS Grid Layout**: Implements CSS Grid with `repeat(auto-fit, minmax(300px, 1fr))` for responsive columns
-   **Responsive Design**: Automatically adjusts the number of columns based on viewport width
-   **Variable Item Sizing**: Some grid items span multiple rows to create visual interest and variety
-   **Clean Spacing**: Consistent 20px gap between grid items for proper spacing
-   **Image Optimization**: Images scale responsively while maintaining aspect ratios
-   **Semantic HTML**: Well-structured HTML with meaningful alt text for accessibility

## Quick Start

1. Clone or download the repository.
2. Open [index.html](index.html) in your browser to preview the testimonial cards.

-   You can also click here to see [The result deployed](https://filipes0.github.io/image-grid)
-   And look the goal: [The goal is this one](https://roadmap.sh/projects/image-grid)

## Exercise Notes

This project serves as a practical exercise in CSS Grid fundamentals:

-   **Grid Structure**: Used `display: grid` with `grid-template-columns: repeat(auto-fit, minmax(300px, 1fr))` to create a flexible column system that automatically wraps items based on available space
-   **Responsive Behavior**: The `minmax(300px, 1fr)` ensures columns are at least 300px wide while growing to fill available space, creating a responsive layout without media queries
-   **Item Spanning**: Applied `grid-row: span 2` and `grid-area: span 2` to select items, creating visual hierarchy and breaking monotony in the grid
-   **Alignment**: Images are constrained with `max-width: 100%` and `max-height: 100%` to fit within their grid cells while maintaining aspect ratios
-   **Gap Management**: Used consistent 20px gap for spacing, improving visual separation between items

## Project Structure

```
testimonial-cards/
├── index.html          # Demo page showcasing the testimonial cards
├── README.md           # This file
├── LICENSE             # MIT License
└── assets/
    └── style.css       # Component styles
```

## Author

-   **LinkedIn:** [FilipeS0](https://linkedin.com/in/FilipeS0)
-   **GitHub:** [FilipeS0](https://github.com/FilipeS0)

## License

This project is available under the MIT License. See the `LICENSE` file for details.

## Feedback

Contributions, suggestions, and PRs are welcome — please open an issue or submit a PR with improvements.

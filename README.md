# Image Grid

A small project demonstrating a responsive image grid built with HTML and CSS Grid.

This repository contains a simple layout that arranges six images into a grid pattern using CSS Grid. The goal is to practice defining grid containers, placing items, and making the layout responsive.

## What I built

-   A responsive grid layout using CSS Grid defined in `assets/style.css`.
-   An HTML structure in `index.html` that places six images into grid items.
-   Basic responsive behavior using `grid-template-columns: repeat(auto-fit, minmax(300px, 1fr))` so items adapt to the viewport.

## Key learning objectives

-   **Grid Structure:** Define a grid container, columns and rows, and how items span multiple rows.
-   **Responsive Design:** Use `auto-fit` / `minmax()` to change layout across viewport sizes.
-   **Alignment and Spacing:** Control gaps and sizing to keep a clean visual rhythm.

## Files

-   `index.html` — markup for the image grid.
-   `assets/style.css` — styles implementing the CSS Grid layout.
-   `assets/images/` — the six images used in the grid.

## How to view locally

Open `index.html` in your browser, or run a simple static server from the project root:

## TODO

-   [x] Create HTML structure and place images
-   [x] Implement CSS Grid layout and responsive columns
-   [ ] Confirm images and styles render correctly on multiple viewports
-   [ ] Add captions and improve accessibility (alt text already included)
-   [ ] Add a live demo / deploy to GitHub Pages

## Notes

The project uses `grid-row: span 2` on a few items to create taller tiles in the layout. You can tweak `minmax(300px, 1fr)` or the `max-width` on the container to change how the grid collapses on smaller screens.

If you'd like, I can add a demo GIF, improve accessibility, or deploy this to GitHub Pages next.

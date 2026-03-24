# Multi-Page CSS-only Website

This project demonstrates how to create a multi-page website using **only HTML and CSS**, without any JavaScript involved.

## Features

*   **CSS-Only Architecture**: Zero JavaScript required for navigation logic.
*   **Single Page Experience**: content updates instantly without refreshing the browser.
*   **Smooth Transitions**: Sections fade in and slide up when navigated to.
*   **Active Link Highlighting**: The navigation menu automatically highlights the current section.
*   **Clean Design**: Uses the 'Montserrat' font family and a soft purple color palette.

## How It Works

1.  **HTML Structure**: All "pages" (Home, About, Services, Contact) are `div` elements placed on top of each other using `position: absolute`.
2.  **Navigation**: Links in the nav bar point to IDs (e.g., `<a href="#about">`).
3.  **CSS Logic**:
    *   By default, sections are hidden (opacity: 0).
    *   When a URL ends with an ID (e.g., `index.html#about`), the element with `id="about"` becomes the `:target`.
    *   The CSS rule `#about:target { opacity: 1; }` makes that specific section visible.
    *   The `:has()` selector is used to style the active navigation link based on the current target.


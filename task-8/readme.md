# CSS-Only Accordion

This project demonstrates a basic accordion component built with HTML and CSS.
## Features

- **Pure CSS**: Logic is handled via CSS selectors and `input[type="checkbox"]`.
- **Toggle Mechanism**: Uses hidden checkboxes and labels to control the visibility of content sections.
- **Smooth Animations**: Includes transition effects for expanding and collapsing content.

## How It Works

The accordion relies on the "Checkbox Hack":
1.  **HTML Structure**: Each section has a hidden `<input type="checkbox">`, a `<label>` (which acts as the clickable header), and a content.
2.  **CSS Logic**: The General Sibling Selector (`~`) is used to style the content paragraph when its corresponding checkbox is checked (`input:checked ~ .content`).
    - `max-height` is toggled between `0px` and a `200px` to create the open/close animation.

## File Structure

- `index.html`: Contains the markup with inputs, labels, and content sections.
- `style.css`: Handles layout, hiding the checkboxes, and the expansion logic/animations.


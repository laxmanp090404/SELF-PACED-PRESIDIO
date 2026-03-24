# CSS Dropdown Navigation Task

## Overview
This task involves the implementation of a simple nav bar featuring a CSS-only dropdown menu.

## File Structure
```
task-4/
├── assets/          # icons   
├── index.html       # main html
├── style.css        # styles and dropdown logic
└── readme.md        # doc
```

## Major CSS Classes & Utility

### Navigation & Layout
| Class | Utility |
|-------|---------|
| `header` | Flex container that aligns the logo, menu, and button across the top of the page. |
| `.menu` | Wraps the navigation list items. |
| `.dropdown` | Applied to the parent `<li>` of the dropdown. Used as the trigger area for the hover effect. |
| `.submenu` | The nested list containing dropdown items. Positioned absolutely and hidden by default. |


### Content & Typography
| Class | Utility |
|-------|---------|
| `.herotext` | Large, bold typography for the main headline. |
| `.highlight` | Utility class that changes text color to the primary theme blue (`#2595f7`). |
| `.herodescription`| Styles the sub-headline text with specific grey scaling (`#666666`) and weight. |

### Interactive Logic
The dropdown mechanism relies on the following relationship:
- **Default State**: `.submenu` has `visibility: hidden` and `transform: translateY(10px)`.
- **Hover State**: `.dropdown:hover .submenu` changes to `visibility: visible` and `transform: translateY(0)`, creating a smooth fade-in and slide-up animation.

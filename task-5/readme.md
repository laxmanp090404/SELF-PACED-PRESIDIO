# CSS-Only Modals

## Overview
Implemented 2 ways for creating modals using only css.

1. **Target Method**: Utilizes the URL fragment identifier and the `:target` pseudo-class.
2. **Checkbox Method**: Utilizes a hidden checkbox input and the `:checked` pseudo-class.

## File Structure

```text
task-5/
├── assets/         
├── index.html       
├── style.css        
└── readme.md       
```
## Key CSS Classes

| Class/ID | Description |
|----------|-------------|
| `.overlay`, `.overlay2` | Full-screen fixed container. Handles the background dimming and centers the modal. Default state is hidden (`opacity: 0`, `visibility: hidden`). |
| `.modal` | The actual content box. Contains the animation logic (e.g., `transform: scale(0.8)` to `scale(1)`). |
| `.close` | Applied to the closing buttons/labels. |
| `#toggle` | The hidden checkbox input driving the second modal instance. |

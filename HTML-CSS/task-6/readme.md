# CSS-Only Tabbed Content

## Description
Created a tabbed content with radio buttons

## Files
- **index.html**: index html file.
- **style.css**: css styles

## How It Works
1. **Radio Buttons**: Two radio inputs (`#tab1`, `#tab2`) act as the state managers. They are hidden from view using `display: none`.
2. **Labels**: Labels are linked to the radio inputs via the `for` attribute. Clicking a visible "tab" (label) checks the underlying hidden radio button.
3. **CSS Logic**: The General Sibling Selector (`~`) checks which radio button is selected and changes the `display`, `opacity`, and `transform` properties of the corresponding `.tabcontent` div.

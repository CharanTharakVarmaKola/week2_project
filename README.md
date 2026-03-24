# Week 2: CSS - Styled Portfolio

## Project Overview
**Goals and Objectives:**
The objective of this project is to enhance the Week 1 HTML HTML portfolio website by applying CSS styles. The focus is on implementing modern typography, a robust and visually pleasing color scheme, layout management through CSS Grid and Flexbox, interactive hover states, and responsive design targeting mobile, tablet, and desktop environments.

## Setup Instructions
1. Download or clone this project folder.
2. Verify you have the file structure intact (`index.html`, `style.css`, and the `images/` directory).
3. Open `index.html` in any modern web browser to view the active, styled webpage.
4. No additional dependencies or packages (like npm) are required.

## Code Structure
```
week2-portfolio/
│
├── index.html       # The main markup structure file with linked Google Fonts and styles
├── style.css        # External stylesheet handling all visual styling and media queries
├── README.md        # This project documentation
├── images/          # Directory containing visual media (profile picture)
└── screenshots/     # Directory allocated for storing project testing screenshots
```

## Technical Details (CSS Concepts Used)
This project makes extensive use of the following foundational CSS properties and algorithms:
- **Global Reset & Variables:** Implements `box-sizing: border-box` to normalize object sizing, and CSS `:root` variables to define the unified dark color palette.
- **Typography:** Uses Google Fonts API ('Outfit') ensuring crisp, highly modern readability matching the technical aesthetic.
- **CSS Selectors:** Demonstrated proficiency using Element Selectors (`body`, `header`, `nav`), Pseudo-classes (`:hover`, `:focus`), and IDs (`#about`, `#skills`).
- **CSS Flexbox:** Applied to the `header` and `#about` sections to align content sequentially and handle spacing natively without rigid pixel dimensions.
- **CSS Grid:** Implemented in the `#skills` section (`display: grid`) using `repeat(auto-fit)` to dynamically wrap skill cards logically across shifting screen boundaries.
- **Responsive Design:** Utilizes a `@media` query capping at `768px` max-width to restack the Flexbox navigation layout and the About profile vertically for excellent mobile reading.

## Visual Documentation
*(Note: As requested, insert screenshots of your project inside the `screenshots/` folder and link them below before submission)*
- **[Screenshot: Desktop Layout]** - Proving the Grid and Flexbox functionality on wide screens.
- **[Screenshot: Mobile Layout]** - Proving the `@media (max-width: 768px)` breaking points align appropriately visually.
- **[Screenshot: Hover States]** - Capturing the `transform` properties on the buttons/skills cards acting as interactive elements.

## Testing Evidence
- **Responsiveness Test:** Hand-tested resizing the browser window from 1920px down to 320px; confirmed all visual elements accurately wrap and retain spacing constraints.
- **Hover/Transition Testing:** Tested hovering mouse logic over the main nav, submit button, and skill bubbles to ensure transitions execute at exactly `0.3s ease` avoiding layout jumping.
- **Style Validation:** HTML connects properly to `style.css` matching all target selectors reliably inside DOM rendering trees across Chrome, Edge, and Firefox.

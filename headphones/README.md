# Headphones - From Design to Implementation

This project is a responsive implementation of a Headphones landing page based on a design from Figma. The goal was to create a pixel-perfect, responsive webpage using only HTML and CSS, without any external frameworks or JavaScript.

## Design

Original design by Nicolas Philippot, UI/UX designer.
- [Figma Design File](https://www.figma.com/file/YOUR_FIGMA_LINK)
- [Final Screens](https://www.figma.com/file/YOUR_FIGMA_LINK/screens)

## Requirements

- No external CSS frameworks (like Bootstrap) allowed
- No JavaScript allowed
- Must be fully responsive
- Must follow accessibility best practices

## Implementation Details

### Technologies Used
- HTML5
- CSS3 (with CSS Grid and Flexbox)
- Responsive Design (Mobile First approach)

### Fonts
1. **Source Sans Pro** - Main font family
   - [Download from Google Fonts](https://fonts.google.com/specimen/Source+Sans+Pro)
2. **Spin Cycle OT** - Used for specific design elements
   - [Download from Font Squirrel](https://www.fontsquirrel.com/fonts/spin-cycle-ot)

### Design Specifications
- **Max width of content**: 1000px (centered on the page)
- **Breakpoint for mobile version**: 480px or less
- **Color scheme**: 
  - Primary: #FF6565 (used for hover/active states)
  - Text: #071629
  - Background: #FFFFFF
  - Footer: #071629

### Interactions
- **Links**: 
  - Hover/Active state: `color: #FF6565`
- **Buttons**:
  - Hover/Active state: `opacity: 0.9`

### File Structure
```
headphones/
├── index.html          # Main HTML file
├── styles/             # CSS styles
│   ├── style.css       # Main styles
│   └── variables.css   # CSS variables
├── assets/             # Images and icons
│   └── images/         # Image assets
└── README.md           # This file
```

## How to View
Simply open the `index.html` file in your web browser to view the webpage locally.

## Responsive Design
- **Desktop**: Full layout with all sections visible
- **Mobile (≤ 480px)**: Stacked layout with adjusted spacing and typography
- **Tablet (481px - 1024px)**: Adjusted layout for medium screens

## Accessibility
- Semantic HTML5 elements used throughout
- Proper heading hierarchy
- ARIA labels where appropriate
- Sufficient color contrast
- Keyboard navigable

## Author
[Reuben Idan] - [GitHub Profile](https://github.com/reuben-dan)

## Acknowledgments
- Nicolas Philippot for the original design
- ALX School for the project guidelines

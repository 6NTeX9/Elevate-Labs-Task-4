# Responsive Website Demo

A mobile-friendly website demonstrating CSS media queries and responsive design principles.

## Features

- **Fully Responsive Layout** - Adapts seamlessly to desktop, tablet, and mobile devices
- **CSS Media Queries** - Three breakpoints for optimal viewing experience
- **Mobile-First Navigation** - Collapsible hamburger menu on smaller screens
- **Flexible Grid System** - Dynamic column layouts that stack on mobile
- **Optimized Images** - Scales properly within containers
- **Modern Design** - Clean, contemporary UI with smooth animations

## Responsive Breakpoints

| Device | Max Width | Layout Changes |
|--------|-----------|----------------|
| Desktop | > 768px | Full multi-column layout |
| Tablet | ≤ 768px | 2-column grids, collapsible nav |
| Mobile | ≤ 480px | Single column, reduced font sizes |

## Key Components

### Navigation
- Sticky header with gradient background
- Hamburger menu for mobile devices
- Smooth toggle animation

### Sections
- **Hero** - Full-width banner with call-to-action
- **Features** - 3 → 2 → 1 column grid
- **Gallery** - 4 → 2 → 1 column image grid
- **Content** - Main content + sidebar (stacks on mobile)

## Testing Instructions

1. Open the HTML file in a web browser
2. Press `F12` or `Ctrl+Shift+I` to open Chrome DevTools
3. Click the device toolbar icon (📱) or press `Ctrl+Shift+M`
4. Test different devices:
   - iPhone SE (375px)
   - iPad (768px)
   - Desktop (1200px+)
5. Use responsive mode to drag and resize

## Technologies Used

- HTML5
- CSS3 (Media Queries, Flexbox, Grid)
- Vanilla JavaScript (Menu toggle)

## File Structure

```
responsive-website/
├── index.html          # Complete single-file website
└── README.md          # This file
```

## CSS Media Query Examples

```css
/* Tablet */
@media (max-width: 768px) {
    .features {
        grid-template-columns: repeat(2, 1fr);
    }
}

/* Mobile */
@media (max-width: 480px) {
    .features {
        grid-template-columns: 1fr;
    }
}
```

## Learning Outcomes

✅ Understanding CSS media queries  
✅ Mobile-first responsive design  
✅ Flexible layouts with CSS Grid and Flexbox  
✅ Image optimization for different screen sizes  
✅ Navigation patterns for mobile devices  
✅ Testing with browser developer tools  

## Browser Compatibility

- Chrome (recommended for testing)
- Firefox
- Safari
- Edge

All modern browsers with CSS3 support.

---

**Task 4: Make a Website Mobile-Friendly Using CSS Media Queries** ✓ Complete
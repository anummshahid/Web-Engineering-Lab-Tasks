# Bahria University Website Replica

This project replicates the Bahria University website (https://bahria.edu.pk/home/index) using only HTML and CSS, following modern web development best practices.

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Semantic HTML**: Uses proper HTML5 semantic elements (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`)
- **CSS Grid & Flexbox**: 
  - CSS Grid for overall page layout
  - Flexbox for component-level layouts
- **Mobile-First Navigation**: Responsive navbar with checkbox hack for mobile menu
- **Modern CSS**: Clean, professional styling with smooth animations and transitions

## File Structure

```
assignment/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── images/             # Image assets
│   ├── logo.svg        # University logo
│   ├── hero-campus.jpg # Hero section image
│   ├── news1.jpg       # News image 1
│   ├── news2.jpg       # News image 2
│   └── news3.jpg       # News image 3
└── README.md           # This file
```

## Key Features Implemented

### 1. Responsive Navigation Bar
- Desktop: Horizontal navigation with dropdown menus
- Mobile: Hamburger menu using checkbox hack (`:checked` pseudo-class)
- Smooth transitions and hover effects

### 2. Hero Section
- Two-column layout with content and image
- Responsive grid that stacks on mobile
- Call-to-action buttons with hover effects

### 3. Quick Links Section
- CSS Grid with `auto-fit` and `minmax()` for responsive cards
- Hover animations and professional styling

### 4. News & Events Section
- Responsive card layout
- Image optimization and proper aspect ratios
- Clean typography and spacing

### 5. Statistics Section
- Animated counters and responsive grid
- Professional color scheme

### 6. Footer
- Multi-column layout with contact information
- Social links and quick navigation
- Responsive design

## Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px

## CSS Techniques Used

1. **CSS Grid**: For overall page layout and responsive card grids
2. **Flexbox**: For navigation, buttons, and component alignment
3. **Media Queries**: For responsive design across devices
4. **CSS Custom Properties**: For consistent theming
5. **Smooth Animations**: Hover effects and transitions
6. **Mobile-First Approach**: Progressive enhancement

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## How to Run

1. Open `index.html` in a web browser
2. Test responsiveness by resizing the browser window
3. Test mobile menu by clicking the hamburger icon on mobile devices

## Code Quality

- **Semantic HTML**: Proper use of semantic elements
- **Clean CSS**: Well-organized styles with meaningful class names
- **Accessibility**: Proper alt text, focus states, and keyboard navigation
- **Performance**: Optimized images and efficient CSS

## Future Enhancements

- Add more interactive elements
- Implement smooth scrolling
- Add loading animations
- Enhance accessibility features

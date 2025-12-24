# Ahmed Yasser Abu Alrob - Portfolio CV

A modern, interactive portfolio website featuring a liquid glass morphism design with smooth animations and an elegant monochrome aesthetic.

## Features

### Design & Aesthetics
- **Liquid Glass Morphism**: Semi-transparent glassmorphic cards with backdrop blur effects
- **Interactive Liquid Blob**: Cursor-following visual element that creates an organic, fluid experience
- **Scroll Progress Indicator**: Fixed sidebar showing reading progress through the page
- **Responsive Typography**: Fluid type scaling that adapts seamlessly from mobile to desktop
- **Monochrome Palette**: Clean black and white design with subtle gray accents

### Interactive Elements
- **Expandable Project Cards**: Click any project to view detailed information in a modal overlay
- **Hover Effects**: Smooth transitions and transforms on interactive elements
- **Smooth Scrolling Animations**: Hero section scales and fades as you scroll
- **Responsive Grid Layout**: Adaptive layouts optimized for all screen sizes

### Content Sections
- Hero introduction with contact information
- Education background
- Professional experience
- Project showcase with detailed modals
- Technical skills organized by category
- Leadership and research achievements
- Certifications

## Technologies Used

- **React 18**: Component-based UI architecture
- **Babel Standalone**: In-browser JSX transformation
- **Modern CSS**: Glassmorphism, backdrop filters, CSS Grid, Flexbox
- **Google Fonts**: Inter (UI) and JetBrains Mono (code/data)
- **Vanilla JavaScript**: Scroll tracking and cursor following

## Setup & Usage

### Quick Start

1. Clone or download the HTML file
2. Open `index.html` directly in any modern web browser
3. No build process or installation required!

### Requirements

- Modern web browser with ES6+ support (Chrome, Firefox, Safari, Edge)
- JavaScript enabled
- Internet connection (for CDN resources)

### Customization

#### Update Personal Information

Edit the content in the JSX sections:

```javascript
// Contact info in hero section
<a href="tel:+962777242105">+962 777 242 105</a>
<a href="mailto:ahmed.abualrob@gmail.com">ahmed.abualrob@gmail.com</a>

// Social links
<a href="https://linkedin.com/in/ahmedyasserabualrob">LinkedIn</a>
<a href="https://github.com/AhmadRob">GitHub</a>
```

#### Add/Edit Projects

Modify the `projects` array in the component:

```javascript
const projects = [
  {
    id: 'unique-id',
    name: 'Project Name',
    type: 'Project Type',
    tech: 'Tech Stack',
    desc: 'Short description',
    details: 'Detailed description',
    link: 'https://project-url.com'
  }
];
```

#### Update Skills

Edit the `skills` object:

```javascript
const skills = {
  'Category Name': ['Skill 1', 'Skill 2', 'Skill 3']
};
```

## Browser Support

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

Older browsers may not support backdrop-filter (glassmorphism effect).

## Performance Optimization

- Minimal dependencies (only React from CDN)
- CSS-based animations for smooth 60fps performance
- Optimized scroll and mousemove listeners with direct state updates
- Single HTML file deployment

## File Structure

```
portfolio-cv/
└── index.html          # Complete standalone application
```

## Deployment

### GitHub Pages
1. Create a new repository
2. Upload `index.html`
3. Enable GitHub Pages in repository settings
4. Access via `https://username.github.io/repository-name`

### Netlify/Vercel
1. Drag and drop the HTML file into the deployment interface
2. Get instant deployment with custom domain support

### Traditional Hosting
Upload `index.html` to any web server and access directly.

## Credits

**Design & Development**: Ahmed Yasser Abu Alrob  
**Fonts**: Inter by Rasmus Andersson, JetBrains Mono  
**Framework**: React by Meta

## License

This portfolio design is free to use as inspiration for your own portfolio. Please update with your own content and information.

---

Built with attention to detail, modern web standards, and a focus on user experience.

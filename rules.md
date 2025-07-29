# Peppa Pig VS Eevee - Website Structure & Guidelines

## 🎯 Project Overview
A multi-page interactive website comparing Peppa Pig and Eevee, featuring modern web technologies, engaging UI/UX, and comprehensive comparison data.

## 📁 Website Structure

### Core Pages
1. **Home Page** (`index.html`)
   - Hero section with animated characters
   - Quick comparison overview
   - Navigation to all sections
   - Featured battles/comparisons

2. **Character Profiles** (`pages/`)
   - `peppa-profile.html` - Peppa Pig detailed profile
   - `eevee-profile.html` - Eevee detailed profile
   - Character stats, abilities, background
   - Interactive character cards

3. **Comparison Pages** (`pages/`)
   - `head-to-head.html` - Direct comparison interface
   - `abilities.html` - Powers and abilities comparison
   - `popularity.html` - Fan following and cultural impact
   - `merchandise.html` - Products and commercial success

4. **Interactive Features** (`pages/`)
   - `battle-simulator.html` - Interactive battle simulation
   - `quiz.html` - "Which character are you?" quiz
   - `polls.html` - Community voting and polls
   - `gallery.html` - Image/video gallery

5. **Community** (`pages/`)
   - `reviews.html` - User reviews and ratings
   - `fan-art.html` - Community submissions
   - `discussions.html` - Discussion forum-style page

6. **Information** (`pages/`)
   - `about.html` - About the project
   - `credits.html` - Sources and acknowledgments
   - `contact.html` - Contact/feedback form

## 🛠️ Technical Guidelines

### HTML5 Standards
- Use semantic HTML elements (`<main>`, `<section>`, `<article>`, `<aside>`, `<nav>`)
- Implement proper accessibility attributes (ARIA labels, alt texts)
- Meta tags for SEO and social media sharing
- Progressive Web App (PWA) capabilities

### CSS Framework
- **Tailwind CSS** (CDN or build process)
- Custom component classes for reusability
- Responsive design (mobile-first approach)
- CSS Grid and Flexbox for layouts
- CSS animations and transitions

### JavaScript (ES6+)
- Modern JavaScript features (arrow functions, destructuring, modules)
- Vanilla JS preferred, minimal dependencies
- Interactive elements and animations
- Local storage for user preferences
- Fetch API for any data loading

## 📚 Recommended Open Source Libraries

### Core Framework
```html
<!-- Tailwind CSS -->
<script src="https://cdn.tailwindcss.com"></script>

<!-- Or install via npm -->
npm install -D tailwindcss
```

### Animation & Interactions
- **AOS (Animate On Scroll)** - Scroll animations
- **GSAP** - Advanced animations
- **Lottie Web** - JSON-based animations
- **Intersection Observer API** - Native scroll detection

### Icons & Graphics
- **Heroicons** - Beautiful hand-crafted SVG icons
- **Phosphor Icons** - Flexible icon family
- **Lucide** - Beautiful & consistent icons

### Utilities
- **Day.js** - Lightweight date manipulation
- **Chart.js** - Interactive charts for comparisons
- **Swiper.js** - Touch slider component
- **Vanilla Tilt** - 3D tilt effects

### Development Tools
- **Vite** - Fast build tool
- **PostCSS** - CSS processing
- **Autoprefixer** - CSS vendor prefixes

## 🎨 Design Guidelines

### Color Palette
- **Peppa Pink**: #FF69B4, #FFB6C1, #FFC0CB
- **Eevee Brown**: #8B4513, #D2B48C, #DEB887
- **Neutral**: #2D3748, #4A5568, #718096
- **Accent**: #3182CE, #38B2AC

### Typography
- **Primary**: Inter, system-ui, sans-serif
- **Headings**: Custom Google Fonts (Nunito, Poppins)
- **Monospace**: Fira Code, monospace

### Responsive Breakpoints
- Mobile: 320px - 767px
- Tablet: 768px - 1023px
- Desktop: 1024px+

## 📂 File Organization

```
eevee_vs_peppa/
├── index.html
├── pages/
│   ├── peppa-profile.html
│   ├── eevee-profile.html
│   ├── head-to-head.html
│   ├── battle-simulator.html
│   ├── quiz.html
│   └── ...
├── css/
│   ├── main.css
│   ├── components.css
│   └── utilities.css
├── js/
│   ├── main.js
│   ├── components/
│   ├── utils/
│   └── data/
├── images/
│   ├── peppa/
│   ├── eevee/
│   └── ui/
├── data/
│   ├── characters.json
│   └── comparisons.json
└── assets/
    ├── fonts/
    └── icons/
```

## 🚀 Development Best Practices

### Performance
- Optimize images (WebP format when possible)
- Lazy loading for images and components
- Minify CSS and JavaScript for production
- Use CDN for static assets
- Implement caching strategies

### Accessibility
- Keyboard navigation support
- Screen reader compatibility
- High contrast color ratios
- Alternative text for all images
- Focus indicators for interactive elements

### SEO Optimization
- Semantic HTML structure
- Meta descriptions and titles
- Open Graph tags for social sharing
- Schema.org markup
- Sitemap.xml generation

### Code Quality
- Consistent naming conventions
- Modular JavaScript architecture
- CSS component methodology
- Code comments and documentation
- Version control with meaningful commits

## 🎯 Interactive Features Implementation

### Battle Simulator
- Character selection interface
- Stat-based battle calculations
- Animated battle sequences
- Result sharing functionality

### Quiz System
- Question database in JSON
- Progress tracking
- Result calculation and display
- Social sharing integration

### Polling System
- Vote storage (localStorage/sessionStorage)
- Real-time result updates
- Visual progress bars
- Prevent duplicate voting

## 📱 Mobile-First Approach

### Touch Interactions
- Swipe navigation between sections
- Touch-friendly button sizes (min 44px)
- Gesture-based image galleries
- Pull-to-refresh functionality

### Performance Optimization
- Critical CSS inlining
- Resource preloading
- Service worker implementation
- Offline functionality basics

## 🔧 Development Workflow

1. **Setup**: Initialize project with basic HTML structure
2. **Styling**: Implement Tailwind CSS and custom components
3. **Content**: Add character data and comparison content
4. **Interactivity**: Implement JavaScript features
5. **Testing**: Cross-browser and device testing
6. **Optimization**: Performance and accessibility improvements
7. **Deployment**: Static site hosting (Netlify, Vercel, GitHub Pages)

## 📊 Content Strategy

### Character Data Structure
```json
{
  "peppa": {
    "name": "Peppa Pig",
    "origin": "UK Children's TV",
    "abilities": ["Jumping in muddy puddles", "Family leadership"],
    "popularity": 95,
    "merchandise": "High"
  },
  "eevee": {
    "name": "Eevee",
    "origin": "Pokémon",
    "abilities": ["Evolution", "Adaptability"],
    "popularity": 98,
    "merchandise": "Very High"
  }
}
```

## 🎨 UI/UX Principles
- Clean, modern design with playful elements
- Consistent navigation across all pages
- Visual hierarchy with proper spacing
- Loading states and micro-interactions
- Error handling and user feedback
- Progressive disclosure of information

---

*This document serves as the master reference for all development decisions. Always refer back to these guidelines when building features or making design choices.*

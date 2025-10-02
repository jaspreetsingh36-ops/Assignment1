# Portfolio Website - Jaspreet Singh

## Project Overview
This is a personal portfolio website built with HTML5 and CSS3 for the INFR3120 Web and Scripting Programming course at Ontario Tech University.

## Live Site
[View Live Portfolio]

## Features
- 4 responsive pages: Home, About Me, Projects, Contact Me
- Dark theme color scheme
- Fluid design with media queries
- Semantic HTML5 elements
- Form validation
- Accessible design

## Gradients Implementation

### Linear Gradient
- **Location:** Header/Navigation bar
- **Code:** `background: linear-gradient(135deg, #1a1a1a, #2d2d2d)`
- **Purpose:** Creates a subtle depth effect in the header while maintaining the dark theme aesthetic.

### Angled Linear Gradient
- **Location:** Submit button on Contact Me page
- **Code:** `background: linear-gradient(45deg, #4a90e2, #357abd)`
- **Purpose:** Provides visual emphasis on the primary call-to-action button with a dynamic 45-degree angle.

## Color Scheme

The color scheme was created using Adobe Color and follows a professional dark theme:

- **Primary Background:** `#121212` (Near black)
- **Secondary Background:** `#1e1e1e` (Dark gray)
- **Primary Text:** `#f0f0f0` (Off-white)
- **Secondary Text:** `#aaaaaa` (Light gray)
- **Accent Color:** `#4a90e2` (Professional blue)

This scheme ensures high contrast for accessibility while maintaining a modern, professional appearance suitable for a cybersecurity student portfolio.

## File Structure
portfolio-site/
├── index.html
├── about.html
├── projects.html
├── contact.html
├── readme.md
├── css/
│ ├── main.css # Base styles
│ ├── mobile.css # Mobile styles (< 768px)
│ ├── tablet.css # Tablet styles (768px - 1024px)
│ └── laptop.css # Laptop styles (> 1024px)
├── images/
│ └── jaspreet-profile.jpg
│ └── video-poster.jpg
└── video/
└── intro.mp4

text

## Viewport Dimensions Used

### Mobile: < 480px
- **Breakpoint**: `max-width: 480px`
- **Reason**: Optimized for smartphones in portrait mode. This breakpoint ensures comfortable touch interactions and readable text on small screens.

### Tablet: 600px - 1024px
- **Breakpoint**: `min-width: 600px and max-width: 1024px`
- **Reason**: Targets tablets in both portrait and landscape orientations, as well as smaller laptops. This range accommodates medium-sized screens with balanced layout.

### Laptop: > 1024px
- **Breakpoint**: `min-width: 1025px`
- **Reason**: Designed for standard laptops and desktop monitors. Utilizes additional screen space for enhanced layouts and better typography.

## Gradients Implementation

### Linear Gradient
- **Location**: Header/Navigation bar across all pages
- **Code**: `background: linear-gradient(135deg, #1a1a1a, #2d2d2d)`
- **Purpose**: Creates visual depth and professional appearance in the header while maintaining consistency with the dark theme.

### Angled Linear Gradient
- **Location**: Submit button on Contact Me page
- **Code**: `background: linear-gradient(45deg, #4a90e2, #357abd)`
- **Purpose**: Provides visual emphasis on the primary call-to-action button with a dynamic 45-degree angle that creates a modern, interactive feel.

## Color Scheme

### Base Color Scheme (Default - All Viewports)
- **Primary Background**: `#121212` (Near black)
- **Header Gradient**: `linear-gradient(135deg, #1a1a1a, #2d2d2d)`
- **Card Background**: `#1e1e1e` (Dark gray)
- **Form Background**: `#1e1e1e` (Dark gray)
- **Input Background**: `#2d2d2d` (Medium dark gray)
- **Footer Background**: `#1a1a1a` (Dark gray)
- **Primary Accent**: `#4a90e2` (Professional blue)
- **Button Gradient**: `linear-gradient(45deg, #4a90e2, #357abd)`
- **Primary Text**: `#f0f0f0` (Off-white)
- **Secondary Text**: `#cccccc` (Light gray)
- **Meta Text**: `#aaaaaa` (Gray)

### Mobile Color Scheme (< 768px) - Deep Navy Blue Theme
- **Body Background**: `#0a1929` (Deep navy blue)
- **Header Gradient**: `linear-gradient(135deg, #0c1a2b, #1e3a5c)`
- **Card Background**: `#102a43` (Dark navy blue)
- **Hero Text Background**: `#102a43` (Dark navy blue)
- **Footer Background**: `#0c1a2b` (Darker navy)
- **Primary Accent**: `#2d7fd7` (Bright blue)
- **Button Gradient**: `linear-gradient(45deg, #2d7fd7, #1e5bb3)`
- **Primary Text**: `#e2e8f0` (Light blue-gray)
- **Secondary Text**: `#cbd5e0` (Blue-gray)
- **Meta Text**: `#a0aec0` (Gray-blue)

### Tablet Color Scheme (768px-1024px) - Charcoal Red Theme
- **Body Background**: `#1a1a1a` (Charcoal black)
- **Header Gradient**: `linear-gradient(135deg, #0f0f0f, #2d2d2d)`
- **Card Background**: `#2d2d2d` (Medium charcoal)
- **Hero Text Background**: `#2d2d2d` (Medium charcoal)
- **Footer Background**: `#0f0f0f` (Dark charcoal)
- **Primary Accent**: `#e53e3e` (Vibrant red)
- **Button Gradient**: `linear-gradient(45deg, #e53e3e, #c53030)`
- **Primary Text**: `#e5e5e5` (Light gray)
- **Secondary Text**: `#d4d4d4` (Gray)
- **Meta Text**: `#a3a3a3` (Light gray)

### Laptop Color Scheme (> 1024px) - Dark Slate Teal Theme
- **Body Background**: `#1e2a3a` (Dark slate blue)
- **Header Gradient**: `linear-gradient(135deg, #1a202c, #2d3748)`
- **Card Background**: `#2d3748` (Medium slate)
- **Hero Text Background**: `#2d3748` (Medium slate)
- **Footer Background**: `#1a202c` (Dark slate)
- **Primary Accent**: `#38b2ac` (Modern teal)
- **Button Gradient**: `linear-gradient(45deg, #38b2ac, #319795)`
- **Primary Text**: `#edf2f7` (Off-white)
- **Secondary Text**: `#e2e8f0` (Light blue-gray)
- **Meta Text**: `#a0aec0` (Gray-blue)

## Color Scheme Rationale
The color schemes were designed to:
1. **Maintain readability** with sufficient contrast ratios
2. **Provide visual variety** across different devices
3. **Use professional, modern color palettes** appropriate for a cybersecurity portfolio
4. **Ensure accessibility** with WCAG compliant color combinations
5. **Create visual hierarchy** through consistent accent colors

## Technologies Used
- **HTML5**: Semantic markup, form validation
- **CSS3**: Flexbox, gradients, media queries, fluid design
- **Responsive Design**: Mobile-first approach with fluid layouts
- **Git/GitHub**: Version control and deployment

## Validation & Testing
- **HTML Validation**: W3C Markup Validation Service 
- **CSS Validation**: W3C CSS Validation Service 
- **Accessibility**: WAVE accessibility tool tested 
- **Spell Check**: Completed with appropriate tools 
- **Link Validation**: All internal and external links verified 

## Browser Compatibility
- Chrome (Latest)
- Firefox (Latest)
- Safari (Latest)
- Edge (Latest)

## Deployment
The site is deployed using GitHub Pages with the following steps:
1. Repository set to public
2. GitHub Pages enabled in repository settings
3. Continuous deployment from main branch

## Version Control
- Regular commits showing progressive development
- Descriptive commit messages
- Well-structured repository
- Public repository for transparency


## Author
**Jaspreet Singh**  
Networking and Cybersecurity Student  
Ontario Tech University  
Email: csinghjaspreet@gmail.com

## License
This project is for educational purposes as part of INFR3120 Web and Scripting Programming course.
This README now includes:

Complete color schemes for all viewports (default, mobile, tablet, laptop)

Specific hex codes for every element

Color scheme rationale explaining the design decisions

Clear organization of colors by viewport and element type

Professional presentation suitable for your assignment submission



# Tech Study Group Website

A responsive website showcasing information about a study group, built with HTML and CSS following IBM's Carbon Design System principles.

## Project Structure

```
Tech Study Group/
├── default.html          # Main landing page
├── default.css           # Global stylesheet
├── images/               # Group images folder
└── members/              # Member profile pages
    ├── 20210001/
    │   ├── 20210001.html
    │   └── images/
    ├── 20210002/
    │   ├── 20210002.html
    │   └── images/
    ├── 20210003/
    │   ├── 20210003.html
    │   └── images/
    ├── 20210004/
    │   ├── 20210004.html
    │   └── images/
    └── 20210005/
        ├── 20210005.html
        └── images/
```

## Features

### Main Page (default.html)
- **Sticky Header**: 
  - Navigation links to all sections (About, Group Photo, Members)
  - Dropdown menu for quick access to individual member pages
  - Mobile hamburger menu that opens a sidebar navigation
- **Breadcrumb Navigation**: Below the header for easy navigation context
- **About Section**: Introduction paragraph about the study group
- **Interactive Group Photo**: 
  - Clickable hotspots over each member's face
  - Hover effects with member names
  - Direct navigation to member profiles
- **Member Directory**: 
  - Grid layout with member cards
  - Profile pictures, roles, and specializations
  - Quick view of contact information
  - Links to full profiles

### Member Profile Pages
Each member has a dedicated profile page featuring:
- Consistent header with navigation
- Breadcrumb navigation below the header
- Profile header with photo and name
- Detailed information grid:
  - Full name
  - Student ID
  - Date of birth
  - Email address
  - Phone number
  - Role in group
  - Specialization
  - Academic year
- About section with personal bio
- Return link to main page

## Design System

### Color Scheme
Based on IBM Carbon Design System:
- **Primary Blue**: `#0f62fe` - Main interactive elements
- **Gray Scale**: Various shades for text and backgrounds
- **White**: `#ffffff` - Clean background

### Typography
- Font Family: IBM Plex Sans (fallback to system fonts)
- Hierarchical heading sizes
- Consistent line height (1.5-1.6) for proper text alignment
- All navigation items share the same baseline

### CSS Architecture
- **BEM Naming Convention**: Block__Element--Modifier pattern for clarity and maintainability
- **Minimal Inline Styles**: All styling in external CSS file
- **Modular Components**: Reusable component classes

### Components
- Cards with hover effects
- Interactive buttons with transitions
- Responsive grid layouts
- Breadcrumb navigation
- Dropdown select menu
- Mobile sidebar navigation

## Responsive Design

### Desktop (> 1024px)
- Multi-column member grid
- Full navigation menu
- Optimized spacing

### Tablet (769px - 1024px)
- 2-column member grid
- Adjusted spacing

### Mobile (≤ 768px)
- Single column layout
- **Sidebar Navigation**: Hamburger menu opens a slide-in sidebar from the right
- Optimized touch targets
- Smaller profile images
- Full-width navigation items

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with flexbox and grid, BEM naming convention
- **Minimal JavaScript**: Mobile menu toggle and dropdown navigation (no external libraries)
- **Lorem Picsum**: Placeholder images

## Team Members

1. **Emma Watson** (20210001) - Team Leader, Full Stack Development
2. **Marcus Johnson** (20210002) - Backend Developer, Database Systems
3. **Aria Martinez** (20210003) - Frontend Developer, UI/UX Design
4. **Kevin Chen** (20210004) - DevOps Engineer, Cloud Computing
5. **Sarah Al-Rahman** (20210005) - Data Scientist, Machine Learning

## How to Use

1. Open `default.html` in a web browser
2. Navigate through sections using the header menu
3. Click on member faces in the group photo to view profiles
4. Use the dropdown menu for quick member access
5. Browse the member directory for an overview of all members

## Features Implemented

✅ Header at the very top with sticky positioning  
✅ Breadcrumb navigation below header on all pages  
✅ Interactive group photo with clickable hotspots  
✅ Member dropdown menu in header  
✅ Mobile sidebar navigation (hamburger menu)  
✅ Responsive design (mobile and desktop)  
✅ IBM Carbon Design System inspired styling  
✅ BEM naming convention for CSS classes  
✅ Minimal inline styling (JavaScript in external script tags)  
✅ Consistent text alignment and baseline for all elements  
✅ Minimal color scheme (blue and grays)  
✅ Clean, professional layout  
✅ Smooth hover effects and transitions  
✅ Accessibility considerations (semantic HTML, ARIA labels, proper contrast)  

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Notes

- All images are sourced from Lorem Picsum for demonstration purposes
- Member information is fictional and for demonstration only
- No external CSS frameworks or JavaScript libraries used
- Pure HTML and CSS implementation

---

© 2025 Tech Study Group. All rights reserved.

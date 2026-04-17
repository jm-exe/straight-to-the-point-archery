# Straight to the Point Archery

## Project Overview

Straight to the Point Archery is a professional archery instruction website designed to showcase classes, instructors, and services for all skill levels — from complete beginners to competitive athletes. The site features a clean, modern design with responsive layouts that work seamlessly across desktop and mobile devices.

The academy offers three structured class levels (A101 Basic, A102 Intermediate, A103 Advanced), private lessons, and expert instruction from certified coaches. The website serves as both an informational hub and a primary entry point for prospective students.

## Features

- **Responsive Design**: Fully responsive layout with mobile-first approach
  - Desktop navigation with full menu
  - Mobile hamburger menu with smooth animations
  - Adaptive grid layouts for all screen sizes
  - Optimized breakpoints at 1024px, 720px, and 560px

- **Multiple Pages**
  - **Home** – Hero section with call-to-action, class overview, and instructor preview
  - **Classes** – Detailed class listings with schedules, prerequisites, and enrollment information
  - **Instructors** – Full instructor profiles with certifications, bio, and teaching focus
  - **About** – Mission statement, facility details, and organizational policies
  - **Contact** – Contact form, location map, and business information
  - **Alternative Homepage** – Secondary landing page variant

- **Accessibility & Performance**
  - Semantic HTML structure for accessibility
  - Organized external CSS files for maintainability
  - CSS variables for consistent theming
  - Smooth animations and transitions
  - Lightweight, optimized assets

- **Professional Branding**
  - Custom color scheme (Forest Green, Brown, Gold, Cream)
  - Montserrat & Open Sans typography
  - Consistent navigation and footer across all pages
  - Call-to-action banners on key pages

## Instructions for Viewing the Site

### Option 1: Local File System
1. Navigate to the project folder: `straight-to-the-point-archery`
2. Open any `.html` file in your web browser:
   - `index.html` – Main homepage
   - `classes.html` – Class listings
   - `instructors.html` – Instructor directory
   - `about.html` – About the academy
   - `contact.html` – Contact information
   

### Option 2: Local Development Server
For best results with linked assets, run a local server:

**Using Python 3:**
```bash
python -m http.server 8000
```
Then visit: `http://localhost:8000`

**Using Python 2:**
```bash
python -m SimpleHTTPServer 8000
```
Then visit: `http://localhost:8000`

**Using Node.js (http-server):**
```bash
npx http-server
```
Then visit: `http://localhost:8080`

### Navigation
- Use the top navigation bar to move between pages
- On mobile (screen width ≤ 720px), tap the hamburger icon (☰) to open/close the menu
- Footer links provide quick access to key sections and policies

## Project Structure

```
straight-to-the-point-archery/
├── index.html                 # Main homepage
├── classes.html              # Class information and enrollment
├── instructors.html          # Instructor profiles
├── about.html                # About page
├── contact.html              # Contact and location
├── README.md                 # This file
├── css/
│   ├── common.css           # Shared styles and responsive design
│   ├── index.css            # Homepage-specific styles
│   ├── classes.css          # Classes page styles
│   ├── instructors.css      # Instructors page styles
│   ├── about.css            # About page styles
│   ├── contact.css          # Contact page styles
│   └── homepage.css         # Alternative homepage styles
├── images/
│   ├── archeryAcademy-logo-white.png
│   ├── instructor-bio-image1.png
│   ├── instructor-bio-image2.png
│   ├── instructor-bio-image3.png
│   ├── instructor-bio-image4.png
│   └── footerImage.jpg
└── js/
    └── (JavaScript files, if any)
```

## Design System

### Color Palette
- **Primary Green** (`#228B22`) – Main accent color
- **Brown** (`#5C4033`) – Navigation and footer background
- **Gold** (`#DAA520`) – Highlights and CTAs
- **Cream** (`#F5F5DC`) – Light backgrounds
- **White** (`#ffffff`) – Card backgrounds and text
- **Text Dark** (`#2a2a2a`) – Primary text color

### Typography
- **Headings & UI** – Montserrat (font-weights: 400, 700, 900)
- **Body Text** – Open Sans (font-weights: 400, 600)
- Loaded via Google Fonts for consistent rendering

### Responsive Breakpoints
- **Desktop** – 1024px and above (full layout)
- **Tablet** – 720px to 1024px (adjusted spacing and grids)
- **Mobile** – Below 720px (hamburger menu, stacked layouts)
- **Small Mobile** – Below 560px (compact spacing and full-width buttons)

## Credits and Acknowledgments

### Development & Design
- **Original Concept & Implementation** – Archery Academy project
- **Responsive Design & Mobile Optimization** – CSS restructuring and hamburger navigation
- **External CSS Architecture** – Separation of concerns with shared and page-specific stylesheets

### Resources & Tools
- **Google Fonts** – Montserrat and Open Sans typefaces
- **Images & Assets** – Provided instructor photos and branding materials
- **Standard Technologies** – HTML5, CSS3, responsive design best practices

### Instructors & Content
- Derek Jenkins (Lead Instructor)
- Amy Smith (Instructor)
- Nathan Lee (Instructor)
- Staff Instructor

### Browser Compatibility
Tested and optimized for:
- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Mobile Safari and Chrome Android

## Getting Started

1. **View the Site**
   - Open `index.html` in your browser or use a local development server

2. **Customize**
   - Edit color variables in `css/common.css`
   - Modify page-specific styling in the respective CSS files
   - Update content in HTML files

3. **Deploy**
   - Upload all files to your web hosting service
   - Ensure CSS and image paths are correct on your server
   - Test all navigation links post-deployment

## Future Enhancements

- JavaScript interactivity for forms and animations
- Backend integration for class enrollment
- Class schedule management system
- Instructor availability calendar
- Online payment processing
- Student portal/dashboard

---

**Last Updated:** April 2026  
**Version:** 1.0  
**Status:** Responsive design implemented with mobile-optimized navigation

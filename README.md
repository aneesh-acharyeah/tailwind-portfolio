# Personal Portfolio Website

## Overview
This is a personal portfolio website built to showcase web development skills, projects, and contact information. The website features a modern, responsive design with a dark mode toggle, smooth scrolling, and animations for an enhanced user experience.

## Features
- **Responsive Design**: Optimized for all screen sizes using Tailwind CSS.
- **Dark Mode**: Toggle between light and dark themes, with user preference saved in localStorage.
- **Smooth Scrolling**: Seamless navigation between sections using JavaScript.
- **Animations**: Fade-in and slide-up animations for a polished look, implemented with Tailwind CSS.
- **Sections**:
  - **Home**: Hero section with a gradient background and call-to-action.
  - **About**: Personal introduction with a placeholder image.
  - **Projects**: Showcase of projects with hover effects and placeholder images.
  - **Contact**: Simple contact form (non-functional, for display purposes).
  - **Footer**: Copyright information.

## Technologies Used
- **HTML5**: Structure of the website.
- **Tailwind CSS**: Styling and responsive design.
- **JavaScript**: Theme toggle, smooth scrolling, and localStorage for theme persistence.
- **CDN**: Tailwind CSS loaded via CDN with custom configuration for animations.

## Setup Instructions
1. **Clone or Download**: Download the project files or clone the repository.
2. **Open `index.html`**: No build steps required; simply open the `index.html` file in a web browser.
3. **Customize**:
   - Replace `YourName` in the navbar, hero, and footer with your name.
   - Update the placeholder image in the About section (`https://via.placeholder.com/300`) with your photo.
   - Replace project images (`https://via.placeholder.com/400x200`) and descriptions with your own projects.
   - Update project links in the Projects section.
   - Customize colors, fonts, or animations in the Tailwind configuration (in `<script>` tag in `<head>`).
4. **Deploy**: Host the static files on any web server or platform (e.g., GitHub Pages, Netlify).

## File Structure
```
portfolio/
├── index.html       # Main HTML file with all sections and scripts
└── README.md        # Project documentation
```

## Usage
- **Theme Toggle**: Click the sun/moon icon in the navbar to switch between light and dark modes.
- **Navigation**: Use the navbar links to jump to sections with smooth scrolling.
- **Contact Form**: Currently a static form for display; add backend functionality for real submissions.

## Future Improvements
- Add backend integration for the contact form (e.g., using Node.js or a serverless function).
- Include more interactive elements, such as a project filter or modal for detailed project views.
- Enhance accessibility with ARIA labels and keyboard navigation.

## License
© 2025 Aneesh G. All rights reserved.

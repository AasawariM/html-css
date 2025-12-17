# W3Schools Homepage Clone

A responsive frontend replica of the famous W3Schools homepage. This project demonstrates proficiency in HTML5, CSS3 layout techniques (Flexbox & Grid), and responsive web design principles.

## Project Description

The goal of this project was to practice complex layout structures, CSS positioning, and responsive media queries without relying on external CSS frameworks like Bootstrap.

## Technologies Used

- HTML5: Semantic structure and markup.
- CSS3:
  - Flexbox: Used for navigation bars and row alignments.
  - CSS Grid: Used for the "Language Cards" sections (PHP, jQuery, Java cards) to manage complex 2D layouts.
  - Media Queries: Extensive use of @media rules to ensure the site adapts to Mobile (max-width: 600px), Tablet, and Desktop screens.
  - Variables: CSS variables for consistent theming.
- JavaScript (Vanilla):
  - Functionality for the interactive "How To" Slideshow.
  - Mobile dropdown menu toggling.

## Key Features

- Responsive Navigation:
  - A sticky top navigation bar that stays fixed while scrolling.
  - A hamburger menu for mobile devices that toggles a dropdown sidebar.
- Hero Section: Recreated with the iconic "Learn to Code" search interface and wave SVG divider.
- Language Sections: Distinct sections for HTML, CSS, and JavaScript with "Try it Yourself" code preview layouts.
- Grid Layouts:
  - colored card grids for various programming languages.
  - Responsive adjustments (changing from 4 columns to 2, and then 1 column on mobile).
- Interactive Components:
  - Slideshow: A functional image slider in the "How To" section with previous/next controls and dot indicators.
  - Hover Effects: Interactive states on buttons, navigation links, and cards.
- Footer: A complete footer implementation with organized link columns and social icons.

## Folder Structure

/
├── index.html # Main HTML structure
├── index.js # JavaScript for slideshow and mobile menu
├── style.css # Global styles and layout
├── mediastyle.css # Specific media queries for responsiveness
├── top-navigation.css # Styles specific to the header/nav
├── mobile-navbar.css # Styles for the mobile drawer menu
└── assets/
└── images/ # Logo, icons, and example images

## How to Run

1.  Clone the repository (if using Git):
    git clone https://github.com/your-username/w3schools-clone.git
2.  Locate the files: Navigate to the folder where you saved the files.
3.  Launch: Open index.html in your preferred web browser (Chrome, Firefox, Edge).

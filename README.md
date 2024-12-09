# Portfolio Website Design Documentation

## Overview
This document outlines the design choices for the portfolio website of Ali Mubiru, providing consistency and a cohesive aesthetic for showcasing professional experiences and projects.

## 1. Typography
- **Primary Font**: *Saira Extra Condensed*
  - Used for headings (`h1`, `h2`, etc.), giving a strong, modern look.
  - Applied to main headings and subheadings for emphasis.

- **Secondary Font**: *Open Sans*
  - Used for body text to ensure readability and contrast with headings.
  - Provides a clean and simple style that is easy on the eyes for longer text.

## 2. Color Scheme
The color scheme follows a professional blue and gray palette to convey reliability and sophistication.

- **Primary Color**: `#3847bd`
  - Used as the main theme color, particularly for the header and navigation bar background (`.bg-primary`).
- **Secondary Color**: `#384abd`
  - Utilized for text highlights (`.text-primary`) to draw attention without overwhelming.
- **Link Colors**: `#412bc3` (primary), `#4a2782` (hover)
  - Links use contrasting shades to enhance visibility and improve user experience.
    ![Screenshot 2024-11-04 215605](https://github.com/user-attachments/assets/193f9778-3b73-46f4-a25f-8b77d43211ec)


## 3. Layout Structure
- **Navigation Bar**: 
  - A fixed side navigation bar (`#sideNav`) provides quick access to different sections of the site. It includes a profile image, which is styled with a rounded border.
  - Uses Bootstrap’s `navbar-expand-lg` and `bg-primary` classes for responsive behavior and color consistency.
    ![Screenshot 2024-11-04 215736](https://github.com/user-attachments/assets/0d5548fe-48cc-41c0-8156-5f145a529955)


- **Section Spacing**:
  - Each section (`.resume-section`) has top and bottom padding to ensure visual separation between content areas.
  - Sections are styled with a border-bottom for a structured look.

## 4. Responsive Design
- **Media Queries**: 
  - The site is optimized for mobile and desktop screens.
  - On larger screens (min-width: 992px), the navigation is fixed to the left, giving more space for the main content.

- **Image Scaling**:
  - The profile and Algonquin College logos have max-width properties to ensure they scale appropriately across devices.

## 5. Icons and Fonts
- **Social Icons**: Font Awesome icons are used for LinkedIn and GitHub profiles in the sidebar, with hover effects for user interaction.
  ![Screenshot 2024-11-04 231512](https://github.com/user-attachments/assets/e9a50a3e-dcb8-49e6-8e55-2fca2bc972d7)

- **Programming Skills**: Icon fonts (Devicons) represent various programming languages and tools, enhancing the visual appeal of the Skills section.
![Screenshot 2024-11-04 231358](https://github.com/user-attachments/assets/6390b016-2943-4dc7-8bbe-b5181921dcc5)


## 6. JavaScript Enhancements
- **Smooth Scrolling**: Enabled by jQuery to create a smooth transition when users click on navigation links.
- **Scrollspy**: Highlights the active section in the navigation bar as users scroll through the content.

## 7. Custom SCSS Components
Several SCSS partials provide structure and modularity for custom styles, ensuring flexibility and easy maintenance:
- **_bootstrap-overrides.scss**: Modifies Bootstrap defaults for specific needs.
- **_global.scss**: Sets global styling, including typography and color variables.
- **_nav.scss**: Customizes the appearance and behavior of the navigation bar.

## 8. Portfolio Section 
- A project entry (`Yatzy Game`) is included in the **Portfolio** section. It outlines the project’s main features and highlights the technology stack used, including JavaScript, HTML, and CSS.
- Developed an (`Emergency Queue`) Management System to streamline patient and admin interactions in emergency settings, it highlights the technology used including Javascript, HTML, CSS, NodeJs and MongoDB. 

## Future Updates
As additional projects or sections are added, this document will be updated to reflect new design components or modifications to existing styles.

---

This design documentation provides a foundation for consistent and thoughtful design choices across the portfolio. It ensures the user experience remains seamless and visually appealing across devices.

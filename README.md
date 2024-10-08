# Project Title: Responsive Web Design with HTML & CSS

## Overview
This project is a fully responsive website that uses modern HTML and CSS practices. It includes various sections like a landing page, features, services, portfolio, about, and contact page. The design adapts to different screen sizes through a combination of media queries and a flexible grid system. The project also uses CSS custom properties (variables) for maintaining a consistent design and allowing easy theme adjustments.

### Key Features:
- **Responsive Design:** The layout adjusts to small, medium, and large screen sizes using media queries.
- **CSS Grid & Flexbox:** These modern CSS techniques are used to create responsive and flexible layouts across different sections.
- **Custom Properties:** CSS variables are used for colors, padding, and transitions, making it easy to update the theme.
- **Smooth Scroll:** The page includes smooth scrolling for better navigation.
- **Hover Effects:** Animations and transitions provide visual feedback for interactive elements like buttons and navigation links.

## Project Structure
### Global Styles
The project uses a set of global variables and rules that ensure consistency and responsiveness across all components.

- **CSS Variables:**
  - `--main-color`: Primary accent color used throughout the project.
  - `--secondary-color`: Secondary color used for backgrounds and text.
  - `--section-padding`: Standard padding applied to all sections.
  - `--text-color`: Default color for paragraph text.
  - `--main-duration`: Duration for CSS transitions.

## Responsive Behavior
The design is fully responsive with the following breakpoints:
- **Small Screens (max-width: 767px):** Layouts adapt to a single-column format. Font sizes and spacing adjust to ensure readability.
- **Medium Screens (min-width: 768px):** Content is arranged in multi-column grids where applicable. The layout becomes more spacious.
- **Large Screens (min-width: 1200px):** The full layout is displayed, with larger padding and font sizes for an optimal desktop experience.

## How to Use
1. Clone or download the project files.
2. Open `index.html` in a web browser to view the website.
3. Customize the CSS variables in the `style.css` file to change the theme colors, padding, or transitions.

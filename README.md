# MyPortfolio

This is a personal portfolio website for showcasing projects, skills, and contact information.

## Project Structure

## Files and Directories

### `index.html`

This is the main HTML file for the portfolio website. It includes the structure and content of the website.

### `assets/css/style.css`

This file contains the CSS styles for the website. It defines the layout, colors, fonts, and other visual aspects of the website.

### `assets/js/script.js`

This file contains the JavaScript code for the website. It includes functions for toggling elements, handling scroll events, and managing the theme.

### `README.md`

This file contains the basic information about the project.

## HTML Structure

The `index.html` file is structured as follows:

- **Header**: Contains the logo, navigation menu, and theme toggle button.
- **Main Content**:
  - **Hero Section**: Introduction and social links.
  - **Stats Section**: Educational background.
  - **About Section**: Information about Mohit Patil.
  - **Skills Section**: List of programming skills and tools.
  - **Contact Section**: Contact information and form.
- **Footer**: Contains the logo and copyright information.

## CSS Styles

The `assets/css/style.css` file defines the styles for the website. It includes custom properties, theme colors, reset styles, and media queries for responsiveness.

## JavaScript Functions

The `assets/js/script.js` file includes the following functions:

- **Element Toggle Function**: Toggles the `active` class on elements.
- **Header Sticky & Go to Top**: Adds sticky behavior to the header and shows the "go to top" button on scroll.
- **Navbar Toggle**: Toggles the navigation menu.
- **Skills Toggle**: Toggles between skills and tools.
- **Dark & Light Theme Toggle**: Toggles between dark and light themes and saves the preference in `localStorage`.

## External Libraries

- **Ionicons**: Used for icons in the website. Included via CDN.

```html
<script type="module" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script>
<script nomodule src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>

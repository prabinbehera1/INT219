# Responsive Portfolio Website with Slick Slider

This is a responsive portfolio website that includes a fully functional mobile navigation menu and a review/testimonial slider using the Slick.js library. The design adapts to different screen sizes and provides a smooth user experience across devices.

## Features

- Responsive Design: The website is fully responsive, adapting to various screen sizes with a smooth layout.
- Slick Slider: Integrated review/testimonial slider with navigation dots for better user engagement.
- Mobile Navigation: A hamburger menu for mobile devices that toggles a side navigation panel.
- CSS Animations: Smooth hover effects and transitions for buttons and cards.
- Custom Grid System: Layout and sections are arranged using a flexible grid structure, making it easier to adjust content.

## Technology Used

- HTML5
- CSS3 (with custom variables for theming)
- JavaScript (jQuery for the Slick slider and DOM manipulation)
- Slick.js (for slider functionality)
- Responsive Design (using media queries)

## Project Structure

```bash
/
├── index.html         # Main HTML file for the website
├── css/
│   ├── styles.css     # Main CSS file for styling the website
│   └── utilities.css  # Utility classes for common styles
├── js/
│   └── script.js      # JavaScript file for Slick slider and mobile nav functionality
├── images/
│   └── ...            # Image assets used in the website
└── README.md          # This file
```

## Getting Started 

### Prerequisites

To run this project, you will need a basic setup of HTML, CSS, and JavaScript. You'll also need to include jQuery and Slick.js, either by CDN or local installation.

INSTALLATION

1. Clone the repository:
```bash
   git clone https://github.com/yourusername/portfolio-website.git
```
   
2. Navigate to the project directory:
   
```bash
cd portfolio-website
```

3.Download and include jQuery and Slick.js:

You can use the CDN versions for ease of setup. Include the following in your index.html:

```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.8.1/slick.min.css" />
<script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.8.1/slick.min.js"></script>
```
4. Run the project:

You can open index.html directly in your browser to view the website.

## How To Use

### Slider

The Slick slider is automatically initialized on page load. The slider is configured to display navigation dots but no arrows.

### Mobile Navigation

The mobile navigation is toggled by the hamburger icon at the top right of the screen. When clicked, it will slide in the mobile navigation, and clicking the close button (x) will slide it out.

### CSS Customization

To change the primary colors or modify styles, you can adjust the CSS variables defined in the :root selector within styles.css.

### JavaScript

The slider and mobile navigation scripts are located in js/script.js.

## Demo


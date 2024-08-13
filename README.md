# Molten CSS Specification - An OpenSource Web Styler
<b>Molten CSS Specification</b> is an open-source web styler that provides comprehensive styling specifications for the core HTML elements. It allows you to focus on writing HTML tags while the styling work is seamlessly handled by the Molten CSS framework.

## Overview
The <b>Molten CSS Specification</b> simplifies web development by predefining styles for various HTML elements and components. This specification includes default themes, responsive elements, and modern CSS features such as transitions and gradients. It ensures consistent design across different devices and browsers, making it easier for developers to create visually appealing websites.

## Features
    • Default Color Theme: A clean, modern look with a white background and neutral text color.
    • Global Styles: Applies transitions and font settings to all HTML elements for a smooth, modern user experience.
    • Typography: Predefined styles for headings, paragraphs, and text elements with optimized spacing and line-height.
    • Navigation Bar: A responsive, shadowed navigation bar suitable for both mobile and desktop devices.
    • Buttons: Various button styles (power, energy, trust) with hover and focus states for enhanced interactivity.
    • Text Effects: Special text classes such as fancy-text for gradient-styled text.
    • Footers: A simple, bold footer style using the 'molten-css-font-Oregon' font.
    • Flexible Spacing: Flags for parent elements that adjust spacing between child elements, with options for major and minor adjustments.
    
## Usage
To use Molten CSS in your project, simply link the CSS file in your HTML:
```html
<link rel="stylesheet" href="path/to/molten.css">
```

Use the predefined classes and flags to style your elements:
```html
<body class="--molten-css-spacing-everywhere-major">
    <nav>Navigation Bar</nav>
    <h1>Welcome to Molten CSS</h1>
    <p>This is a paragraph styled with Molten CSS.</p>
    <button class="molten-css-power-button">Click Me</button>
    <footer>© 2024 Molten CSS</footer>
</body>
```

## Font Integration
Molten CSS integrates custom fonts to enhance the visual appeal of your website. The specification includes a variety of font styles that can be easily applied using the font-family property.

### Example
```css
body {
    font-family: 'molten-css-font-Quicksand', Arial;
}
```

# Contributing
Contributions are welcome! If you'd like to contribute to the Molten CSS Specification, please fork the repository and create a pull request with your changes.

# License
Molten CSS is licensed under the MIT License. For more details, please refer to the LICENSE file.

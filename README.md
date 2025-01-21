# Soyab Documentation

## Overview
This project comprises a simple HTML file and an accompanying CSS file. The purpose of this project is to demonstrate the creation of a visually appealing representation of the letters in the word "SOYAB" using CSS transformations and animations.

## HTML Structure
The HTML document defines the basic structure of the webpage. It consists of metadata in the `<head>` section and the content in the `<body>` section. A main container holds individual span elements, each representing a single letter with a `data-title` attribute.

### Head Section
- **Title**: Sets the title of the webpage.
- **Meta Charset**: Specifies the character encoding for the document.
- **Meta Viewport**: Ensures the webpage is responsive and adjusts correctly to different screen sizes.

### Body Section
- **Main Container**: A `div` element with a class of `container` that holds all the spans.
- **Span Elements**: Individual spans each containing a letter and a matching `data-title` attribute for styling purposes.

## CSS Styling
The CSS file provides the necessary styling for the HTML elements, including setting font properties, positions, colors, and applying transformation effects. Key sections include:

### Body
- **Margin & Padding**: Removed to eliminate default space around the body.

### Container
- **Text Alignment**: Centers the content horizontally.
- **Margin**: Adds top and bottom margins and centers the container horizontally.
- **Font**: Specifies the font family to use.

### Span Elements
- **Font Size & Color**: Sets the size and color of the text.
- **Positioning**: Utilizes relative positioning to allow for absolute positioning of pseudo-elements.
- **Text Shadow**: Adds a shadow effect to the text.

### Pseudo-elements (:before and :after)
- **Content**: Uses the `data-title` attribute to display text content.
- **Positioning**: Positioned absolutely within the span.
- **Transformations**: Applies 3D rotations and other transformations for visual effects.
- **Z-index**: Layers elements to create a 3D effect.

### Hover Effects
- **Perspective**: Applies a 3D perspective transformation on hover.
- **Rotation & Scale**: Alters the rotation and scale of the pseudo-elements on hover to enhance interactivity.

## Usage
To use or view this webpage:
1. Open the HTML file in any modern web browser.
2. Modify the content of the HTML or the styles in the CSS file to customize the appearance as desired.

## License
This project is licensed under the MIT License, allowing for free use, modification, and distribution.


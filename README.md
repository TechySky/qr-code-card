# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H).

## Table of contents

- [Overview](#overview)
- [Screenshot](#Screenshot)
  - [Desktop Preview](#Desktop-Previewh)
  - [Tablet Preview](#Tablet-Preview)
  - [Mobile Preview](#Mobile-Preview)
- [Links](#Links)
- [Built with](#Built-with)
- [Author](#Author)

## Overview

This code is a basic HTML and CSS solution for the Frontend Mentor QR code component challenge.

The HTML code includes a head section with meta tags for character encoding and viewport settings, as well as links to the CSS stylesheet (style.css) and favicon.

The body section contains a div with the class "page-container", it height is equal viewport height and it includes another div with the class "qr-container".The qr-container div contains an image tag that displays the QR code and a div with the class "textimonials" that includes a heading and paragraph.

The CSS code starts with a font import from Google Fonts and sets global styles for all elements. The body background color is set to a light shade of blue, and the font family is set to "Outfit". The page-container div is set to fill the entire viewport, and the qr-container div is positioned absolutely in the center of the page using a transform and top/left values.

The max-width of the qr-container is set to 320px, and it is made responsive with flexbox by using display: flex and flex-direction: column. The qr-image is given a max-width of 288px and is centered with border-radius of 10px. The textimonials div is also given a max-width of 288px and is centered with flexbox, with a gap of 1rem between the heading and paragraph. The h2 heading is styled with the Outfit font, bold font-weight, and a blue color. The paragraph text is also styled with the Outfit font, a lighter font-weight, and a gray color.

Finally, a media query is used to adjust the styles for smaller screen sizes. The qr-container and textimonial text sizes are decreased, and the max-width of the qr-container is reduced to 250px.

## Screenshot

### Desktop Preview

![](./screenshots/Web%20capture_27-2-2023_183513_127.0.0.1.jpeg)

### Tablet Preview

![](./screenshots/Web%20capture_27-2-2023_183544_127.0.0.1.jpeg)

### Mobile Preview

![](./screenshots/Web%20capture_27-2-2023_183619_127.0.0.1.jpeg)
![](./screenshots/Web%20capture_27-2-2023_18365_127.0.0.1.jpeg)

### Links

- Solution URL: https://github.com/TechySky/qr-code-card
- Live Site URL: https://qr-code-card-techy.netlify.app/

### Built with

- HTML
- CSS custom properties
- Flexbox

## Author

- Frontend Mentor - https://www.frontendmentor.io/profile/TechySky
- Twitter - https://twitter.com/techysky_lk
- Youtube - https://www.youtube.com/@techysky_lk

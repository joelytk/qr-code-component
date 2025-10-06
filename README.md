# QR code component

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H)

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

I created a simple QR code component using HTML and CSS.

### Screenshot

![Desktop](./images/screenshot-desktop.png)
![Mobile](./images/screenshot-mobile.png)

### Links

- Solution URL: [Frontend Mentor - QR code component](https://your-solution-url.com)
- Live Site URL: [QR code component](https://joelytk.github.io/qr-code-component)

## My process

1. I started by creating the HTML skeleton of all the necessary components (card, card image, card title and card text).
2. After that, I declared all the CSS variables from the style guide and placing it into the ::root pseudo-class.
3. After declaring the CSS variables, I added the default styling using the universal selector.
4. I used flexbox for the body and made sure the height spanned across the full viewheight of the device.
5. Finallu, I styled the card image, card title and card text according to the design.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I used to think that you could only create box-shadow colors with opacity percentages using rgba(). Today, I learned that you can do it using rgb() as well. You just have to omit the commas and separate the absolute color values with spaces:

```css
.card {
  box-shadow: 0px 25px 25px 0px rgb(0 0 0 / 0.0477);
}
```

### Useful resources

- [box-shadow](https://developer.mozilla.org/en-US/docs/Web/CSS/box-shadow) - I used this page to help me write the rgb() values in the box-shadow CSS property correctly. I really liked this pattern and will use it going forward.
- [Bootstrap Card Example](https://getbootstrap.com/docs/5.3/components/card/#example) - This is an amazing article which I constantly refer to when I want to create cards using HTML and CSS. I'd recommend it to anyone still learning this concept.

## Author

- Website - [Joel Yap](https://github.com/joelytk)
- Frontend Mentor - [@joelytk](https://www.frontendmentor.io/profile/joelytk)

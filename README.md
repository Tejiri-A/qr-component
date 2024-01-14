# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [HTML structure](#html-structure)
  - [CSS styling](#css-styling)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

This is my attempt on the frontend menthor qr code component challenge designed for beginners in HTML and CSS

### Screenshot

![Desktop view](./screenshots/Desktop%20screenshot.png)
![Mobile view](./screenshots/mobile%20screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/Tejiri-A/qr-component)
- Live Site URL: [Add live site URL here](https://tejiri-qr-component-solution.netlify.app/)

## My process

In this section, I will share how I developed a QR code component using HTML and CSS. A QR code component is a simple web page that displays a QR code image and some text. The QR code can be scanned by a mobile device to visit a website or perform some action. The text provides some information about the QR code and the website it links to.

## HTML structure

The HTML structure of the QR code component consists of two main elements: a `<main>` element and a `<footer>` element. The `<main>` element contains the QR code image and the text, while the `<footer>` element contains the attribution links.

The `<main>` element has a class of `card` to apply some styling. Inside the `<main>` element, I used an `<img>` element to display the QR code image. The image source is a local file called `image-qr-code.png`. The image also has an `alt` attribute that describes the image content for accessibility purposes.

Below the `<img>` element, I used a `<h1>` element to display the main heading of the text. The heading says "Improve your front-end skills by building projects". This is the main message that I want to convey to the users who scan the QR code.

Below the `<h1>` element, I used a `<p>` element to display the subheading of the text. The subheading says "Scan the QR code to visit Frontend Mentor and take your coding skills to the next level". This is the secondary message that I want to convey to the users who scan the QR code. It also provides a call to action for them to visit the website.

The `<footer>` element has a class of `attribution` to apply some styling. Inside the `<footer>` element, I used two pairs of `<p>` and `<a>` elements to display the attribution links. The first pair says "Challenge by Frontend Mentor" and links to the Frontend Mentor website. The second pair says "Coded by Oghentejiri Amrasa" and links to my GitHub profile.

## CSS styling

The CSS styling of the QR code component consists of three main parts: variables, global reset, and element-specific styles.

The variables part defines four custom properties for the colors used in the component. The colors are white, light gray, grayish blue, and dark blue. The custom properties are prefixed with `--` and can be accessed using the `var()` function.

The global reset part applies some common styles to all elements and pseudo-elements. It sets the margin, padding, and box-sizing properties to zero. It also sets the text-size-adjust property to none to prevent the browser from resizing the text based on the device. It also sets the margin-block-end property to zero for the body, h1, and p elements to remove the default margins.

The element-specific styles part applies some specific styles to the html, body, img, h1, p, main, and footer elements. It also uses media queries to make the component responsive for different screen sizes.

The html element sets the font-family property to Outfit, a Google font that I imported using the `@import` rule. It also sets the background property to the light gray color.

The body element sets the text-align property to center to align the content horizontally. It also sets the display property to flex and the align-items and justify-content properties to center to align the content vertically. It also sets the flex-direction property to column to stack the content vertically. It also sets the min-height property to 100vh to make the body fill the viewport height. 

The img element sets the max-width property to 100% to make the image responsive. It also sets the display property to block to remove the default space below the image. It also sets the border-radius property to 0.6rem to round the corners of the image. It also sets the margin-bottom property to 1.2rem to create some space below the image.

The h1 element sets the font-size property to 1.4rem and the color property to the dark blue color. It also sets the line-height property to 1.1 to reduce the space between the lines of the heading. It also sets the text-wrap property to balance to distribute the words evenly across the lines. It also sets the margin-bottom property to 1.2rem to create some space below the heading.

The p element sets the font-size property to 0.96rem and the color property to the grayish blue color. It also sets the font-weight property to lighter to make the text less bold. It also sets the margin-bottom property to 1.4rem to create some space below the paragraph.

The main element sets the background property to the white color and the max-width property to 20rem to limit the width of the card. It also sets the padding property to 1rem to create some space inside the card. It also sets the border-radius property to 1.2rem to round the corners of the card. It also sets the box-shadow property to 2px 8px 18px rgb(0, 0, 0, 0.1) to create a subtle shadow effect for the card.

The footer element sets the position property to absolute and the bottom property to zero to place the footer at the bottom of the page. It also sets the display property to flex and the font-size property to 0.6875rem to make the footer compact. It also sets the text-align property to initial to align the text to the left. It also sets the color property of the a elements to hsl(228, 45%, 44%) to make the links stand out.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I learned the correct way to reset the style attributes of the HTML elements, how to accomodate both the card component and the attribution within the viewport without the need for scrolling and the use :not pseudo-class selector to negate a specific element.

```css
*,
*::after,
*::before {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

html {
  -webkit-text-size-adjust: none;
  -moz-text-size-adjust: none;
  -ms-text-size-adjust: none;
  text-size-adjust: none;
}

body,
h1,
p {
  margin-block-end: 0;
}

p:not(footer > p) {
  font-size: 0.96rem;
  color: var(--grayish-blue);
  margin-bottom: 1.4rem;
  font-weight: lighter;
}
```

### Continued development

I'll like to explore various methods of displaying multiple card components for e-commerce websites (for instance) with the use of flexbox or grid.

## Author

- Frontend Mentor - [@Tejiri-A](https://www.frontendmentor.io/profile/Tejiri-A)
- Github - [Tejiri-A](https://github.com/Tejiri-A)

# qr-component

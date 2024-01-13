# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
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

- I started by creating a basic HTML structure with the `<!DOCTYPE html>`, `<html>`, `<head>`, and `<body>` tags.
- Inside the `<head>` tag, I added some meta tags to specify the character encoding, the viewport settings, and the favicon image. I also added a `<title>` tag to give the page a name.
- I linked the external CSS file with the `<link>` tag, using the `rel`, `href`, and `type` attributes.
- Inside the `<body>` tag, I created a `<section>` tag with a class of `section-center` to contain the main content of the page. I used flexbox to center the content vertically and horizontally.
- Inside the `<section>` tag, I created a `<div>` tag with a class of `card` to represent the QR code component. I gave it a white background, a fixed width, and a border radius. I also added some padding and text alignment properties.
- Inside the `<div>` tag, I added an `<img>` tag to display the QR code image. I used the `src` and `alt` attributes to specify the image source and alternative text. I also gave it a width of 100% and a border radius to match the card.
- Next, I added an `<article>` tag with a class of `card-info` to contain the text content of the component. I gave it some padding to create some space around the text.
- Inside the `<article>` tag, I added a `<h3>` tag to display the main heading of the component. I gave it a dark blue color and a bottom margin.
- Finally, I added a `<p>` tag to display the paragraph of the component. I gave it a grayish blue color, a smaller font size, and a bottom margin.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I learned how to accomodate both the card component and the attribution within the viewport without the need for scrolling. To achieve this, I defined the height of the attribution section and subtracted it from 100% of the viewport height (100vh) using the calc finction to determine the height of the section that contains the card component.


```css
.section-center {
  height: calc(100vh - 1rem);
}

.attribution {
  height: 1rem;
}
```

### Continued development

I'll like to explore various methods of displaying multiple card components for e-commerce websites (for instance) with the use of flexbox or grid.

## Author

- Frontend Mentor - [@Tejiri-A](https://www.frontendmentor.io/profile/Tejiri-A)
- Github - [Tejiri-A](https://github.com/Tejiri-A)



# qr-component

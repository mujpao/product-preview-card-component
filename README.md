# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

Desktop:

![](./solution-images/solution-desktop.png)

Mobile:

![](./solution-images/solution-mobile.png)

### Links

- Solution URL: [GitHub repo](https://github.com/mujpao/product-preview-card-component)
- Live Site URL: [GitHub Pages](https://mujpao.github.io/product-preview-card-component/)

## My process

### Built with

- Flexbox

### What I learned

Some things I learned about for this project were CSS Flexbox, media queries, and the `<picture>` element.
To make the left and right side of the card have equal width and height on desktop, I used Flexbox, setting `flex: 1;` on both child elements.
I used a media query to change the width of the card and change `flex-direction` to `row` on desktop.
Also, I used the `<picture>` element so that different image sizes could be used depending on the width of the screen.

One thing I struggled with initially was that there was a blank space between the bottom of the image and its containing div. I set `vertical-align: middle;` on the image to fix this problem.

### Continued development

I want to keep learning about Flexbox and Grid.

### Useful resources

- [MDN article about responsive images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images) - This helped me learn about the art direction problem and how to use different image sizes depending on the viewport width.
- [Stack Overflow question about image inside div](https://stackoverflow.com/questions/5804256/image-inside-div-has-extra-space-below-the-image) - This helped me with getting rid of the gap at the bottom of the image.
- [The Odin Project](https://www.theodinproject.com/) - This has been a helpful resource for learning about full-stack development.

## Author

- Website - [mujpao](https://github.com/mujpao)
- Frontend Mentor - [@mujpao](https://www.frontendmentor.io/profile/mujpao)

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](/images/127.0.0.1_5500_index.html.png)

### Links

- Solution URL: [Github](https://github.com/reeperc3/Product_Preview_Card)
- Live Site URL: [Github Pages](https://reeperc3.github.io/Product_Preview_Card)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- SCSS and SASS

### What I learned

Discovered how to use SCSS variables and how to configure SASS and SCSS in general.

```scss
// Primary
$green-500: hsl(158, 36%, 37%);
$green-700: hsl(158, 42%, 18%);

// Neutral
$black: hsl(212, 21%, 14%);
$grey: hsl(228, 12%, 48%);
$cream: hsl(30, 38%, 92%);
$white: hsl(0, 0%, 100%);

@media screen and (max-width: 660px) {
    .card {
        grid-template-columns: 1fr;
        width: 90vw;

        img {
            width: 100%;
            content: url("/images/image-product-mobile.jpg");
            border-radius: 10px 10px 0px 0px;
            object-fit: cover;
        }
    }
}
```

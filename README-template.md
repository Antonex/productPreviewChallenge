# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./screenshot.jpg)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

Learned how to use media queries properly, improved my understaning of it and look to improve even further

```css
@media screen and (max-width: 790px) {
  .container {
    flex-direction: column;
    align-items: center;
    justify-content: center;
    margin: 2rem;
    height: auto;
    width: auto;
    background-color: var(--White);
    border-radius: 1rem;
  }

  .container .prod_img img {
    height: 20rem;
    width: 25rem;
    object-fit: cover;
    border-radius: 1rem 1rem 0 0;
  }

  .container .prod_details {
    padding: 2rem 3rem 2rem 2rem;
    background-color: var(--White);
    height: auto;
    width: 25rem;
    border-radius: 0 0 1rem 1rem;
  }
}

```
## Author

- Frontend Mentor - [Antonex](https://www.frontendmentor.io/profile/Antonex)
- Facebook - [ANTO](https://www.facebook.com/profile.php?id=100080671484819)

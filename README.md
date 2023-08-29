# Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

- Desktop

  ![](./images/desktop_view.jpg.jpg)

- Mobile

  ![](./images/mobile_view.jpg)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

Learned about some minutiae surrounding color theory in UI design and employed Flexbox and Grid in the layout.

```css
@media screen and (max-width: 650px) {
  .container {
    display: grid;
    grid-template-columns: 100%;
    height: 600px;
    width: 350px;
  }
}
```

### Continued development

I would like to be more thoughtful when naming classes in HTML.
Also next time I would implement a **Mobile First Design** approach.

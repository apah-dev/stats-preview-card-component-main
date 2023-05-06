# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [GitHub](https://github.com/apah-dev/stats-preview-card-component-main.git)
- Live Site URL: [Live Site](https://apah-dev.github.io/stats-preview-card-component-main/)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Learnt how to use media queries for specific break points
Learnt how to use the row-reverse of the flexbox element to flip the layout
Learnt how to use the background-image for a better use of overlay instead of the image tag

To see how you can add code snippets, see below:

```html
<div class="image-container">
  <!-- <img class="image" src="images/image-header-mobile.jpg" alt="header" /> -->
  <div class="image"></div>
  <div class="overlay"></div>
</div>
```

```css
.image-container {
  width: 100%;
  position: relative;
  border-top-left-radius: 0.5rem;
  border-top-right-radius: 0.5rem;
}

.image {
  background-image: url(./images/image-header-mobile.jpg);
  background-repeat: no-repeat;
  background-size: cover;
  min-height: 200px;
  border-top-right-radius: 0.5rem;
  border-top-left-radius: 0.5rem;
}

.overlay {
  position: absolute;
  top: 0;
  left: 0;
  background-color: var(--Softvioletopaque);
  width: 100%;
  min-height: 200px;
  border-top-right-radius: 0.5rem;
  border-top-left-radius: 0.5rem;
  opacity: 1;
}
```

### Useful resources

- [w3schools](https://w3schools.com) - This helped me to understand the use of the background element

- [stackoverflow](https://www.example.com) -

## Author

- Frontend Mentor - [@apah-dev](https://www.frontendmentor.io/profile/apah-dev)
- Twitter - [@benson_apah](https://www.twitter.com/benson_apah)

## Acknowledgments

I thank me for not giving up on me

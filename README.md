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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./screenshot_desktop.png)
![](./screenshot_mobile.png)

### Links

- Solution URL: [on Frontend Mentor](https://www.frontendmentor.io/solutions/stats-preview-card-component-fgskJT1zM5)
- Live Site URL: [on Github](https://pykm.github.io/stats-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Using `background-blend-mode` property to let the element's background image blend with the element's background color.

```html
<main>
  <div class="text-info">
  </div>
</main>
```
```css
main::before{
  background-blend-mode: multiply;
  background-color: var(--accent-color);
  background-image: var(--mobile-decorative-image);
  background-position: center top;
  background-repeat: no-repeat;
  background-size: cover;
}
```

### Continued development

Technique that I'm not completely familiar with, can be found in this challenge:
-  `background-blend-mode` property.

Technique that I found useful, although not using in this challenge:
- SASS

### Useful resources

- [background-blend-mode on MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/background-blend-mode) - This helped me to blend the element's background image with the element's background color.

## Author

- Website - [PYkm](https://pykm.github.io/)
- Frontend Mentor - [@PYkm](https://www.frontendmentor.io/profile/PYkm)

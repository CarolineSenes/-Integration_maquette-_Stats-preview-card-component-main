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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge
The challenge is to build out this card component and get it looking as close to the design as possible.
Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![Desktop version](https://github.com/CarolineSenes/-Integration_maquette-_Stats-preview-card-component-main/blob/master/design/screenshot_desktop.png)
![Mobile version](https://github.com/CarolineSenes/-Integration_maquette-_Stats-preview-card-component-main/blob/master/design/screenshot_mobile.png)


### Links

- Solution URL: [GitHub](https://github.com/CarolineSenes/-Integration_maquette-_Stats-preview-card-component-main)
- Live Site URL: [GitHub Pages](https://carolinesenes.github.io/-Integration_maquette-_Stats-preview-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

Even though I didn't use it in the end, I learn more about the `picture` HTML element. It contains zero or more `source` elements and one `img` element to offer alternative versions of an image for different display/device scenarios.

The browser will consider each child `source` element and choose the best match among them. If no matches are found—or the browser doesn't support the `picture` element—the URL of the `img` element's src attribute is selected. The selected image is then presented in the space occupied by the `img` element.

I could have used it this way:
```html
    <picture>
      <source
        srcset="images/image-header-desktop.jpg"
        media="(min-width: 800px)"
      />
      <img src="images/image-header-mobile.jpg" alt="" />
    </picture>
```

I finally preferred to integrate the image as a background in the css.


### Continued development

For small projects that don't require SASS, I will continue using CSS custom variables.

### Useful resources

- [MDN - Picture element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/picture) - It helped me to switch between different image formats depending on the screen size.

## Author

- Website - [Caroline ALEXANDRE](https://www.carolinealexandre.fr) ... in construction ...
- Frontend Mentor - [@CarolineSenes](https://www.frontendmentor.io/profile/CarolineSenes)
- Twitter - [@senes_caroline](https://twitter.com/senes_caroline)
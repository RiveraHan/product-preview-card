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
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview



### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot
### Desktop

![Desktop](./design/desktop-design.jpg)
### Mobile

![Mobile](./design/mobile-design.jpg)

### Links

- Solution URL: [GitHub](https://github.com/RiveraHan/product-preview-card)
- Live Site URL: [Site](https://preview-card-product.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I implemented the mobile first as a priority to implement the css, I understood a little more about grid and flex box as well as the declaration of variables. Start to understand about measurements(media query)

To see how you can add code snippets, see below:

```css
:root {
    /* Colors */
    /* Primary */
    --dark-cyan: hsl(158, 36%, 37%);
    --cream: hsl(30, 38%, 92%);
    --secondary-color: hsl(158, 44%, 20%);
    /* Neutral */
    --very-dark-blue: hsl(212, 21%, 14%);
    --dark-grayish-blue: hsl(228, 12%, 48%);
    --white: hsl(0, 0%, 100%);
  
    /* Fonts */
    --montserrat-font: "Montserrat", sans-serif;
    --fraunces-font: "Fraunces", serif;
  }
  .card {
        display: grid;
        grid-template-columns: 1fr 1fr;
        width: 600px;
        height: 480px;
        background-color: var(--white);
    }
```


### Continued development

I need to learn more about grid and its benefits, about what I should and shouldn't do with all the css properties.

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@RiveraHan](https://www.frontendmentor.io/profile/RiveraHan)
- Twitter - [@rivera_hanzell](https://twitter.com/rivera_hanzell)

## Acknowledgments

I relied on a solution from [MDN](https://developer.mozilla.org/es/docs/Web/CSS/CSS_Grid_Layout/Basic_Concepts_of_Grid_Layout), he helped me understand how I can useful Grid
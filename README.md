# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)



## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Links

- Solution URL: [GitHub](https://your-solution-url.com)
- Live Site URL: [GitHub Page](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow



### What I learned

Used grid-column property, grid-row property, span 2, etc. span 2 means you are spanning across two columns. Use grid-column(this is a short hand) instead of using grid-column-start and grid-column-end, also use grid-row instead of grid-row-start and grid-row-end. 
grid-column: start value / end value;
grid-row: start value / end value;

To see how you can add code snippets, see below:


```css
.col-span-2 {
    grid-column: span 2;
}

.testimonial:last-child {
    grid-column: 4;
    grid-row: 1 / span 2;
} 
```


### Useful resources

- [Learn CSS Grid the easy way by Kevin Powell](https://www.youtube.com/watch?v=rg7Fvvl3taU) - This helped me to place things in specific places, also working with media queries i.e. with mobile-first flow then to other display screen.

- [Complete Grid Tutorial with Cheat Sheet 2021 || CSS Grid 2021](https://www.youtube.com/watch?v=VXW1r09Y6Tw) - This is an amazing article which helped me to understand how css grid works. I'd recommend it to anyone still learning tabout CSS Grid.



## Author

- Frontend Mentor - [@ikquilibrium-SG](https://www.frontendmentor.io/profile/Ikquilibrium-SG)

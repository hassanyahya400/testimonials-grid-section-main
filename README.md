# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./design/desktop-design.jpg)

![](./design/mobile-design.jpg)

Here is a screen shot of the project

### Links

- Solution URL: [Add solution URL here](https://hsn-ng.github.io/testimonials-grid-section-main/)
- Live Site URL: [Add live site URL here](https://github.com/hsn-ng/testimonials-grid-section-main)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

The major concept I learnt in this project if CSS grid;

I spend many hours to discover how to use

```
margin:auto
```

with grid

```css
.container {
  width: 90%;
  margin: auto;
  display: grid;
  gap: 1rem;
  padding-top: 2rem;
  padding-bottom: 2rem;
}

@media (min-width: 1024px) {
  .container {
    /* height: 100%; */
    grid-template-columns: repeat(4, 1fr);
    grid-template-rows: repeat(2, 1fr);
  }

  .lg-1 {
    grid-column: span 2;
  }

  .lg-2 {
    grid-column: span 2;
  }

  .lg-3 {
    grid-row: span 2;
  }
}
```

### Continued development

i'll like to continue smashing as many as possible challenges from Frontend Mentor

### Useful resources

- [Css Tricks](https://css-tricks.com/snippets/css/complete-guide-grid/) - This helped me to understand grid
- [MDN](https://developer.mozilla.org/) - This is an amazing css documentation site

## Author

- Website - [Hassan A Y](https://www.your-site.com)

- Twitter - [@bri_riyadh](https://twitter.com/bro_riyadh)

## Acknowledgments

Kudos to Frontend Mentors

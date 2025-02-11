# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./design/desktop-preview.jpg)

## My process

### Built with

- Semantic HTML5 markup
- BEM architecture
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I have gained knowledge of CSS Grud Layout, including how fractional units(fr) work to create a flexible and responsive designs.

```css
.cards {
  margin-top: 3rem;
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 1.5rem;
}
```

### Continued development

For future project, I want to dive deeper into CSS Grid, particularly grid rows, and make this project more complex. For example, I plan to use a 2fr unit layout for tablet screens.

### Useful resources

- [CSS Grid Layout Module](https://www.w3schools.com/css/css_grid.asp) - This is an amazing article which helped me finally understand Grid. I'd recommend it to anyone still learning this concept.
- [CSS Grid Garden](https://cssgridgarden.com/) - This website helped me understanding grid visually. I really liked their challenges.

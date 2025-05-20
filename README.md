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


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./images/Screenshot%202025-05-20%2011.57.06%20AM.png )


### Links

- Solution URL: [GitHub](https://github.com/Anjie-MF/FEM_testimonialsGrids_figmaChallenge)
- Live Site URL: [GitHub Pages](https://anjie-mf.github.io/FEM_testimonialsGrids_figmaChallenge/)


## My process

### Built with

- Semantic HTML5 markup
- CSS Grid
- Desktop-first workflow


### What I learned


```
.test blockquote {
    grid-column: 1 / -1;
    grid-row: 3;
    margin: 0;
    font-weight: 500;
    font-size: 1rem;
    line-height: 140%;
    color: #ffffff;
    margin: 16px 0px 0px 0px;
}

At first, I was using grid-column: 1/3 to span two columns, but I noticed it looked not balanced and I wanted it to stretch across the entire div. So,I realized that hard-coding the end line could break if the grid layout ever changed. So I switched to 1/-1 to make the blockquote span the full width of its container in a future-proof way. 

```
```
TL:DR - No matter, how may colums are added later, it is flexible and spans the full width of the grid container. 

**TIP**It doesn't mean it ends only in column 1. It just stretches to the end of the specificed column. Check Useful Resources for link.
```

### Continued development

In this project, I noticed there were many repeatable elements. Next time, I want to explore using custom CSS properties. 


### Useful resources

- [mdn_web_docs -- Grid Columns](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-column) - A visual explaintation I really liked.
- [css_tricks --Difference Between Implicit & Explicit Grids ](https://css-tricks.com/difference-explicit-implicit-grids/) - When working on CSS grid, bookmark it.  I'd recommend it to anyone still learning this concept.


## Author

- Linkedin - [Anjelica May](www.linkedin.com/in/anjiemay23)
- Frontend Mentor - [Anjie-MF](https://www.frontendmentor.io/profile/Anjie-MF)



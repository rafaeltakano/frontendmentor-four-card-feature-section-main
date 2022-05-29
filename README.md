# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### Screenshot

![](./design/desktop-preview.jpg)

### Links

- Solution URL: [https://rafaeltakano.github.io/frontendmentor-four-card-feature-section-main/](https://rafaeltakano.github.io/frontendmentor-four-card-feature-section-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [Sass](https://sass-lang.com/) - For styles

### What I learned

I learned more about css grid columns/rows start and end

```css
&__cards {
  grid-template-columns: repeat(3, 1fr);
  grid-template-rows: repeat(2, 1fr);
  justify-items: center;
  align-items: center;

  :nth-child(1) {
    grid-column: 1 / 2;
    grid-row: 1 / 3;
  }

  :nth-child(4) {
    grid-column: 3 / 4;
    grid-row: 1 / 3;
  }
}
```

## Author

- LinkedIn - [Rafael Takano](https://www.linkedin.com/in/rafaeltakano1/)
- Frontend Mentor - [@rafaeltakano](https://www.frontendmentor.io/profile/rafaeltakano)

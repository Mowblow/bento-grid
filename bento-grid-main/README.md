# Frontend Mentor - Bento grid solution

This is a solution to the [Bento grid challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)

  - [The challenge](#the-challenge)
  - [Links](#links)

  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)

- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I learned a lot about grid and layouts in general.

```css
main {
  display: grid;
  grid-auto-columns: 1fr;

  grid-template-areas:
    "seven one one four"
    "seven one one four"
    "seven one one four"
    "seven two three four"
    "seven two three four"
    "eight two three four"
    "eight two three four"
    "eight six five five"
    "eight six five five"
    "eight six five five";
  column-gap: 20px;
}
```

### Continued development

I want to continue improving my knowledge on CSS grids and CSS positions. I also want to learn how to keep my code clean and simple.

### Useful resources

- [CSS grid cheat sheet](https://grid.malven.co/) - This resource helped me recall the important aspects of grid without having to read through a long article.
- [Video-Kevin Powell](https://youtu.be/rg7Fvvl3taU?si=1dd8_obB_iiaz6B9) - This was literally my key to solving this project. Highly recommend watching if you don't have a solid grasp on grid yet.

## Author

- Frontend Mentor - [@mowblow](https://www.frontendmentor.io/profile/mowblow)
- Twitter - [@moblazer005](https://www.twitter.com/moblazer005)

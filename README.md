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
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./images/screenshotstat.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/victorsonet/victorsonet.github.io)
- Live Site URL: [Add live site URL here](https://victorsonet.github.io/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

This was the first time I used mix-blend-mode and this was the first project where the desktop and mobile design was different (with other projects you just had to change the width of the elements) so it was a pretty good practice.

To see how you can add code snippets, see below:

```css
.image-wrapper img {
    display: block;
    border-top-right-radius: 15px;
    border-bottom-right-radius: 15px;
    height: 100%;
    width: 100%;
    mix-blend-mode: screen;
    opacity: 1;
}

.image-wrapper::after {
    content: '';
    position: absolute;
    top: 0;
    right: 0;
    mix-blend-mode: multiply;
    background: var(--accent);
    opacity: 1;
    width: 100%;
    height: 100%;
    z-index: 99;
    border-top-right-radius: 15px;
    border-bottom-right-radius: 15px;
}
```

## Author

- Website - [Viktor Kovács](https://victorsonet.github.io/)
- Frontend Mentor - [@victorsonet](https://www.frontendmentor.io/profile/victorsonet)
- Twitter - [@GMLvictorsoN](https://www.twitter.com/GMLvictorsoN)


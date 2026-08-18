# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./Screenshot%202026-08-18%20at%2015-22-20%20Frontend%20Mentor%20Blog%20preview%20card.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned
  
In my QR Code Component challenge, I implemented the custom fonts with an @import rule in my stylesheet, but I decided to try to implement the custom fonts using @font-face rules for this challenge since I was less familiar with them. I learned that they allow local custom fonts to be used if they are downloaded, and in that aspect, @font-face rules seem to allow more granuluar control over custom fonts than using @import.


```css
@font-face {
  font-family: "Figtree";
  src:
    local("Figtree"),
    url(./assets/fonts/Figtree-VariableFont_wght.ttf) format("truetype");
  font-weight: 300 900;
  font-style: normal;
}

@font-face {
  font-family: "Figtree";
  src:
    local("Figtree"),
    url(./assets/fonts/Figtree-Italic-VariableFont_wght.ttf) format("truetype");
  font-weight: 300 900;
  font-style: italic;
}
```

### Continued development

Admittedly, I was not very familiar with implementing custom fonts with CSS using the @font-face rule. I had to research the @font-face rule to be able to utilize the custom fonts provided for this challenge, but now that I am familiar with how it is used, I feel confident adding it to my toolbox for future projects.

### Useful resources

- [MDN Web Docs - @font-face CSS at-rule](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/At-rules/@font-face) - This was a helpful reference for using the @font-face rule.  

## Author

- GitHub - [@bertomjr](https://github.com/bertomjr)
- Frontend Mentor - [@bertomjr](https://www.frontendmentor.io/profile/bertomjr)


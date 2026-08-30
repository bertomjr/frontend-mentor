# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

![](./assets/images/Screenshot%202026-08-30%20at%2000-23-38%20Frontend%20Mentor%20Social%20links%20profile.png)
![](./assets/images/Screenshot%20From%202026-08-30%2000-24-23.png)


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

This challenge really exposed my gaps in knowledge when it came to CSS transitions. I hard trouble implementing the smooth transition between the grey and green color on the links, but after researching the `transition` property, more specifically `transition-duration` and `transition-timing-function`, I was able to makw the colors transfer smoothly. 

To see how you can add code snippets, see below:


```css
.social-links a {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100%;
    color: var(--white);
    text-decoration: none;
    background-color: var(--grey-700);
    border: 1px solid transparent;
    border-radius: var(--spacing-100);
    padding: var(--spacing-150);
    transition: background-color 500ms ease-out, color 500ms ease-out;
    
}
.social-links a:hover, .social-links a:focus, .social-links a:focus-visible {
    background-color: var(--green);
    color: var(--grey-900);
    cursor: pointer;
    transition-duration: 100ms;
}
```

### Continued development

I will continue to practice utilizing CSS transitions so that I have a better understanding of which properties to add/inspect when faced with problems.


### Useful resources

- [MDN Docs - transition-duration](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Properties/transition-duration) - In the Figma prototype, I noticed that the green color appeared much more quickly than it faded away, but I could not replicate this until researching this property, along with `transition-timing-function`
- [MDN Docs - transition-timing-function](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Properties/transition-timing-function) - I only had a vague understanding of the `linear`, `ease`, `ease-in`, transition timing functions in CSS, this was a helpful reference to gain a more solid understanding.


## Author

- Frontend Mentor - [@bertomjr](https://www.frontendmentor.io/profile/bertomjr)
- GitHub - [@bertomjr](https://github.com/bertomjr)


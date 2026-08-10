# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### Screenshot

![](./images/Screenshot%202026-08-09%20at%2002-09-29%20Frontend%20Mentor%20QR%20code%20component.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom variables
- Flexbox
- CSS Grid

### What I learned

I am proud of the following CSS, because it validated my knowledge of how custom CSS variables could be used. I attribute my familiarity and comfort with using CSS variables to my time spent earning freeCodeCamp's Responsive Web Design certification.

```css
:root {
  --white: hsl(0, 0%, 100%);
  --slate-300: hsl(212, 45%, 89%);
  --slate-500: hsl(216, 15%, 48%);
  --slate-900: hsl(218, 44%, 22%);
  --spacing-200: 16px;
  --spacing-300: 24px;
  --spacing-500: 40px;

  --txt-p1-size: 22px;
  --txt-p1-line-height: 120%;
  --txt-p1-letter-spacing: 0px;
  --txt-p1-font-weight: 700;
  --txt-p1-color: var(--slate-900);
  --txt-p2-size: 15px;
  --txt-p2-line-height: 140%;
  --txt-p2-letter-spacing: 0.2px;
  --txt-p2-font-weight: 400;
  --txt-p2-color: var(--slate-500);

  --background-color: var(--slate-300);
  --qr-code-background: var(--white);
}
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

### Continued development

Although I am already fairly comfortable with Responsive Design concepts, I did have small complications in completing this project.

- I had trouble placing the qr-card-container exactly in the middle of the viewport as intended, and elements within the card elongated when the viewport shrank to a certain width. This caused me to review grid and flexbox practices to fix the issue and I will continue to do so until I am more comfortable placing elements responsively. 

### Useful resources

- [freeCodeCamp](https://www.freecodecamp.com) - This is a great resource for learning about and practicing fundamental web development skills. Personally, I really appreciate all of the workshops and guided projects you get to create, it helps to understand how projects are built.

- [Boot.Dev](https://www.boot.dev) - This is another great resource for learning programming. Although their focus is more on backend development, they also have guided projects and interactive lessons that are engaging. I found the Linux and Git courses to be the most immediately helpful to me so far, but I still have a lot to learn.

## Author

- Frontend Mentor - [@bertomjr](https://www.frontendmentor.io/profile/bertomjr)
- GitHub - [@bertomjr](https://github.com/bertomjr)



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


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./images/Screenshot_1.png)
![](./images/Screenshot_2.png)


### Links

- [Solution URL](https://github.com/BMcdavitt/femStatsPreviewCard)
- [Live Site URL](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I used CSS 'Variables' for the color pallett for the first time:


```css
:root {
  --colorMainBackground: hsl(233, 47%, 7%);
  --colorCardBackground: hsl(244, 38%, 16%);
  --colorAccent: hsl(277, 64%, 61%);

  --colorWhite: hsl(0, 0%, 100%);
  --colorTransparentWhiteMainParagraph: hsla(0, 0%, 100%, 0.75);
  --colorTransparentWhiteStatHeadings: hsla(0, 0%, 100%, 0.6);
}

body {
  color: var(--colorWhite);
  background-color: var(--colorMainBackground);

}
```

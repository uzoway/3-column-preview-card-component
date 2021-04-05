# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)
- [Appreciation](#appreciation)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![Screenshot of Solution](./Screenshot (12).png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Desktop-first workflow

### What I learned

I took on this challenge to refresh some of my Frontend coding skills. Some of which are:

- Using the CSS flexbox
- Building a single webpage which is responsive on various mobile screen sizes.
- Creating animation on page load.

Below is a code snippet of how I animated each Column layout on page load.

```css
/** Animation for each column **/

@keyframes animate{
    0%{
        transform: translateX(-5rem);
    }
    100%{
        transform: translateX(0);
    }
}

@keyframes animate2{
    0%{
        transform: translateY(-5rem);
    }
    100%{
        transform: translateY(0);
    }
}

@keyframes animate3{
    0%{
        transform: translateX(5rem);
    }
    100%{
        transform: translateX(0);
    }
}
```

### Continued development

Moving on, animation is one part of css I have not mastered, so for my next couple of projects, I'm going to ensure I play around with animations. Just like they say, PRACTICE makes PERFECT.

## Author

- GitHub - [uzoway](https://github.com/uzoway)
- Frontend Mentor - [@uzoway](https://www.frontendmentor.io/profile/uzoway)
- Twitter - [@Uzoway_](https://twitter.com/Uzoway_)
- LinkedIn - [Uzochukwu Victor Okafor](https://www.linkedin.com/in/uzochukwu-victor-okafor-0702a2188/)

## Appreciation

I'll like to thank the entire team at [Frontend Mentor](https://www.frontendmentor.io). for putting together yet another wonderful design to help Developer build realistic projects.
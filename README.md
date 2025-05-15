![preview](/images/preview.jpg)

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
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![Desktop preview](/images/testimonial-grid-sc-desktop.png)
![Ipad preview](/images/testimonial-grid-sc-iospad.png)
![IOS 11 preview](/images/testimonial-grid-ios11.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- CSS custom properties
- CSS Grid
- Responsive design
- SASS

### What I learned

Learnt how to properly use css grid properties. Was stuck in somewhere during the process but this lines of code was a game changer for me:
```css
    main{
    width: 80%;
    max-width: 1200px;
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    grid-template-rows: auto;
    gap: 1.7rem;
    place-content: center;
}
```

### Continued development
Will work on more front-end mentor projects in future.

## Author
- Frontend Mentor - [@markorrente01](https://www.frontendmentor.io/profile/markorrente01)

## Acknowledgments
Special thanks to [Front-end Mentor](https://www.frontendmentor.io/) for the resources provided for all projects.

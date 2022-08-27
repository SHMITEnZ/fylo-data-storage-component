# Frontend Mentor - Fylo data storage component solution

This is a solution to the [Fylo data storage component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/fylo-data-storage-component-1dZPRbV5n). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

I made this using a mobile first workflow and added 2 media queries for the desktop version 

Breakdown point at 376px (mobile version) and 900px (switch to the vertical mobile layout as the horizontal layout starts to breakdown but keeping the desktop background image)

### Screenshot

![Desktop_Fylo data storage component](/screenshoots/Desktop_Fylo data storage component.jpg)

![Mobile_Fylo data storage component](/screenshoots/Mobile_Fylo data storage component.jpg)

### Links

- Solution URL: [https://github.com/SHMITEnZ/fylo-data-storage-component](https://github.com/SHMITEnZ/fylo-data-storage-component)
- Live Site URL: [https://shmitenz.github.io/fylo-data-storage-component/](https://shmitenz.github.io/fylo-data-storage-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Responsive design

### What I learned

The main layout is made with CSS flexbox
The floating message was positioned with the position property: absolute in both the desktop and mobile layouts.
The speach-bubble shape of the desktop layout is created with the ::before pseudo element.
Below the code:

```css
..message::before{
        content: "";
        width:0;
        height:0;
        border-style: solid;
        border-width: 3.5rem 0 0 3.5rem;
        border-top-color: #fff;
        border-left-color: transparent;
        position: absolute;
        bottom:-2.5rem;
        right:0;
    }
```

### Useful resources

- [MDM ::Before pseudo-element](https://developer.mozilla.org/en-US/docs/Web/CSS/::before) -  pseudo elemente ::before
- [W3 School](https://www.w3schools.com/css/css_positioning.asp) - This position property 

## Author

- Github - [SHMITEnZ](https://github.com/SHMITEnZ)
- Frontend Mentor - [@SHMITEnz](https://www.frontendmentor.io/profile/SHMITEnZ)


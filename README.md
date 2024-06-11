# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

The solution is a static page in which only HTML and CSS were used for its creation, it is a page in which you can see a cooking recipe divided into: image in the upper part, short title and description of the recipe, preparation time, ingredients, procedure and nutritional table.

### Screenshot

[![Mobile](https://i.postimg.cc/ZKK7RHLP/creenshot-mobile.jpg)](https://postimg.cc/rz3CZS3z)

### Links

- Solution URL: [Add solution URL here](https://github.com/VicManuel-Jiro/PracticaFrontEndMentor_RecipePage)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

It was created by structuring the content using divs and the respective labels of each element such as h1, h2, h3, img, p and table, the recommended fonts and colors were used except for the border of the preparation time and it was done with the Mobile-first workflow.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

In general, I already knew almost everything necessary to perform the task, however there were some moments in which I needed to do a quick search to obtain the best possible result, such as centering the bullet points of the unordered lists so that they were centered vertically in list item since I didn't know how to do this, until I found how to handle it with "::marker" and "::before".

```css
ul li::marker {
    font-size:1rem;
    color: var(--Dark-Raspberry);
}
ul li::before {
    content: "\2022"; 
    position: absolute;
    left: 0;
    top: 50%;
    transform: translateY(-50%); 
    font-size: 20px; 
    line-height: 1;
}
```
## Author

- Website - [Victor Manuel Jiménez Rosas](https://vicmanuel-jiro.github.io/Portafolio/)
- Frontend Mentor - [@VicManuel-Jiro](https://www.frontendmentor.io/profile/VicManuel-Jiro)


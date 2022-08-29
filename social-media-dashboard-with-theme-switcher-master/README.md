# Frontend Mentor - Social media dashboard with theme switcher solution

This is a solution to the [Social media dashboard with theme switcher challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-media-dashboard-with-theme-switcher-6oY8ozp_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page
- Toggle color theme to their preference

### Screenshot

![dark](./dark.jpg)
![light](./light.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Vanilla Javascript


### What I learned

I leant how to use grid and how use javascript to change theme

```html
<div class="grid-cont"></div>
<div class="grid-ano-cont"></div>
```
```css
.grid-cont{
    display: grid;
    grid-template-columns: 1fr 1fr 1fr 1fr;
    grid-template-rows: 175px;
    column-gap: 2.143em; 
}

.grid-ano-cont{
    display: grid;
    grid-template-columns: 1fr 1fr 1fr 1fr;
    grid-template-rows: 115px 115px;
    gap: 1.786em 2.143em;
}
```
```js
const switchs = document.getElementById("switch");

switchs.addEventListener("change",function (){
    document.body.classList.toggle("dark")
})
```


### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

### Useful resources

- [Toggle switch](https://codepen.io/mburnette/pen/LxNxNg) - It helped me in making the toggle switch using checkbox.


## Author

- Name - Ola-Balogun Taiwo
- Frontend Mentor - [@Tiazzy](https://www.frontendmentor.io/profile/Tiazzy)
- Twitter - [@TayworT](https://www.twitter.com/TayworT)

## Acknowledgments

Marcus Burnette for his codepen on toggle switch,which helped me greatly

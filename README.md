# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action


## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow


### What I learned

I applied for the first time my knowledge in css grid, I feel more comfortable with flexbox but I took this project as a challenge to apply my css grid skills. Was not too hard, in fact the only hard part during the development was trying to a mid height for the paragraph next to the $29. I only had to apply the relative-absolute relation between the paragraph and the container for the number and this element. 

```html
<div class="price">
  <span class="amount">&dollar;29</span>
  <span class="month">per month</span>
  </div>
```
```css
.price{
    position: relative;
}
.month{
    font-size: 1em;
    position: absolute;
    margin-top: 9px;
    margin-left: 12px;
    font-weight: 200;
    color: rgb(238, 238, 238);
    opacity: 0.7;
}
```


### Continued development

I still need to improve my ways to center elements in a responsive way. Position and margins aren't the best approach to get responsive websites. 

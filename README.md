# Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- -media Quries


### What I learned

1. CSS VARIABLES :
   .root{ --primary-color:red;
   }
   
   body{
   color:var(--primary-color)
   }

2. I leaned to add CSS resets

3. data-icon in html and css
'''
   <button class="button" data-icon="cart">Add to Cart</button>

'''
'''
.button[data-icon="cart"]::before{
    content: "";
    background-image: url(images/icon-cart.svg);
    width: 15px;
    height: 16px;
}
'''
4. using is in css

.button:is(:hover, :focus){
    background-color: var(--prymary-clr2);
    transition: 0.5s;
}


### Useful resources

- https://www.w3schools.com/) - Basicly answered all the question.

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)


## Acknowledgments

Kevin Powell

https://www.youtube.com/watch?v=B2WL6KkqhLQ&ab_channel=KevinPowell

He help to make this project in every step

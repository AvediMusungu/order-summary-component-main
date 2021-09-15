# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor]

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
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

- See hover states for interactive elements

### Links

- Solution URL: https://avedimusungu.github.io/order-summary-component-main/

## My process

### Built with

- Atom

### What I learned

I learnt how to properly use the **div** elements and **class** tags together in creating objects in HTML and formatting them in CSS.

```html
<div class="sub-box">
      <img class="sub-box-1" src="images/icon-music.svg" alt="">
      <p class="sub-box-2">
        <strong>Annual Plan</strong> <br> $59.99/year
      </p>
      <p class="sub-box-3"><a href="#">Change</a></p>
</div>

```
```css
.sub-box {
  background-color: hsl(225, 100%, 98%);
  border-radius: 20px;
  margin: 0 10%;
  width: 80%;
}

.sub-box-1 {
  width: 12.5%;
  float: left;
  margin-top: 1em;
  margin-left: 1em;
}

.sub-box-2 {
  display: inline-block;
  margin: 1em 5em 1em 1em;
}

.sub-box-3 {
display:inline-block;
float: right;
margin-top: 1.5em;
margin-right:1em;
}

```

### Continued development

-Get more comfortable using **class** tags and **div** elements.
-Get more comfortable with CSS positioning elements/attributes.

### Useful resources
- https://www.w3schools.com/html/html_images_background.asp - This article helped me understand how to incorporate background images into my html.
- https://stackoverflow.com/questions/15550560/background-image-not-displaying-in-chrome-browser - This helped me understand the effect of adblockers on background images. Helpful reminder.
- https://www.codecademy.com/learn/learn-css/modules/learn-css-display-positioning/cheatsheet - This article helped me review the positioning concepts in CSS.

## Author

- Frontend Mentor - [@AvediMusungu](https://www.frontendmentor.io/profile/AvediMusungu)


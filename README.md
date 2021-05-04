# Frontend Mentor - Huddle Landing Page With Single Introductory Section Solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![Mobile View Screenshot](./images/landing-page-mobileview-screenshot.png)

#### Mobile View Screenshot

![Desktop View Screenshot](./images/landing-page-webview-screenshot.png)

#### Desktop View Screenshot

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Media Queries

### What I learned

I was able to figure out the best way to display a perfectly rounded border line around the social media icons. The easiest to achieve this is to make the height, width and border-radius the pixel size.

I used the css code below to achieve this:

```html
<div class="social-media-btns">
  <ul>
    <li>
      <a href="#">
        <i class="fab fa-facebook-f"></i>
      </a>
    </li>
  </ul>  
</div>
```
```css
.social-media-btns ul li a i {
  width: 30px;
  border: 1px solid white;
  height: 30px;
  border-radius: 30px;
  padding-top: 5px;
  text-align: center;
}
```

## Author
- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)
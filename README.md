# Frontend Mentor - FAQ accordion card solution

This is a solution to the [FAQ accordion card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/faq-accordion-card-XlyjD0Oam). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

- Build out the project to the designs provided

### Links

- Solution URL: [Solution on Frontend Mentor](https://www.frontendmentor.io/solutions/social-proof-section-H56JMikZ6)
- Live Site URL: [Github Pages Link](https://landon345.github.io/frontendmentor-social-proof-section/)

## My process

### Built with

- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

In this project, I learned about relative and absolute positioning for background images. I also learned a little bit about javascript.

```html
<div class="illustration-woman">
  <div class="illustration-box"></div>
  <div class="bg-pattern"></div>
</div>
```

```css
@media screen and (min-width: 1000px) {
  .bg-pattern {
    position: relative;
    background: url("./images/bg-pattern-desktop.svg") center center no-repeat;
    top: -550px;
    left: -300px;
    width: 966px;
    height: 945px;
    z-index: 2;
  }
  .illustration-woman {
    position: relative;
    background: url("./images/illustration-woman-online-desktop.svg") center
      center no-repeat;
    width: 472px;
    height: 359px;
    top: 0px;
    left: -120px;
    z-index: 5;
  }
  .illustration-box {
    position: relative;
    background: url("./images/illustration-box-desktop.svg") center center
      no-repeat;
    width: 191px;
    height: 184px;
    top: 150px;
    left: 20px;
    z-index: 10;
  }
}
```

## Author

- Website - [Landon Schlangen](https://www.landonschlangen.com)
- Frontend Mentor - [@Landon345](https://www.frontendmentor.io/profile/Landon345)
- LinkedIn - [Profile](https://www.linkedin.com/in/landon-schlangen-a3989a16b/)

## Acknowledgments

I completed this one on my own in about 3 hours. It was quite a bit more difficult than the other newbie challenges.

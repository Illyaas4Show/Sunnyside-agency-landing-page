# Frontend Mentor - Sunnyside agency landing page solution

This is a solution to the [Sunnyside agency landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/sunnyside-agency-landing-page-7yVs3B6ef).

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

### Screenshot

![](./front-end%20files/screenshot.jpg)

### Links

- Solution URL: [](https://github.com/Illyaas4Show/Sunnyside-agency-landing-page)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- SCSS

### What I learned

I really struggled on this project and it took me way too long, but I have learn a lot along the way. I used SCSS for the first time! It was very frustrating to get started because my Mac was having problems with the installation and it slowed me down an awful lot, but it was more fun when it finally worked. I haven't learnt all of it's features but I have learnt nesting and `@use` and `@forword`. I also reminded myself of the power of CSS-grids as I hadn't used it in a long time due to the use of flex-box. I also learnt to use Emmet to make coding faster. I also learnt to style another element when an element is hovered:

```css
/* If element2 is directly inside element1 */
.element1 > .element2 {
  color: red;
}

/* If element2 is next to element1 */
.element1 + .element2 {
  color: red;
}

/* If element2 is somewhere inside element1 */
.element1 .element2 {
  color: red;
}

/* If element2 is the sibling of element1 */
.element1 ~ .element2 {
  color: red;
}

```

I also learnt how to make a mobile navigation bar. However It wasn't the most functional so I will try to work on that.

I also learnt about the `<Picture>` element, used to add adaptive images:

```html

<picture>
  <source srcset='/mobile-image.jpg' media='(min-width: 500px)'>
  <img src='/desktop-image.jpg' alt=''>
</picture>

```


### Continued development

I will continue to learn to optimize SCSS to make styling easier. I will also experiment in installation to make it less stressful and make it compatible with netlify. It doesn't currently work with netlify unfortunately.

### Useful resources

- [Stack overflow](https://stackoverflow.com/) - This website is really useful for asking questions you have. Other people have already asked my questions so I didn't have to ask them and got the questions.
- [W3Schools](https://www.w3schools.com/) - This website is really useful for learning or checking any coding concept. I use it a lot to remind myself of some syntax.

## Author

- Frontend Mentor - [@Illyaas4Show](https://www.frontendmentor.io/profile/Illyaas4Show)
- Github - [@Illyaas4Show](https://github.com/Illyaas4Show)

## Acknowledgments

- [Kevin Powell](https://www.youtube.com/kepowob) - He is an amazing person that taught me a lot of CSS through his youtube channel. I would definitely recommend you to check him out!

Thank you for viewing!
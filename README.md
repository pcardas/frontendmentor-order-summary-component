# Frontend Mentor - Order Summary Card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

## Overview

### The challenge

- Build a Order Summary Card Component project using the designs provided on the design folder, which contains:
  - Desktop Design
  - Desktop Preview
  - Mobile Design
  - Active States Preview

### Screenshot

- [Desktop Preview](my-solution/desktop-solution.png)
- [Mobile Preview](my-solution/mobile-solution.png)

### Links

- [Solution URL](https://www.frontendmentor.io/solutions/responsive-order-summary-card-CTLFA8S8V)
- [Live Site URL](https://pcardas.github.io/frontendmentor-order-summary-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Desktop-first workflow

### What I learned

I tried to apply some concepts about "rem" units, which ended up being pretty useful during the component development.

- Using "CSS Grid" to get a better dimensional result

```css
.plan {
  display: grid;
  grid-template-columns: 1fr 3fr 1fr;
}
```

- Setting media queries / Setting the mobile background image

```css
@media (min-width: 290px) {
  html {
    font-size: 37.5%;
  }

  body {
    background-image: url(images/pattern-background-mobile.svg);
    background-size: cover;
  }
}
```

### Continued development

Important points that I need to develop:

- Responsiveness (media queries)
- Positioning (specially with backgrounds and images)
- Nomenclature (mainly when naming classes)

### Useful resources

- [Stack Overflow](https://stackoverflow.com/) - Pretty nice explanations from other developers.
- [CSS Tricks](https://css-tricks.com/) - Helpful guides. On this project, it helped a lot with flex and properties.
- [W3Schools](https://www.w3schools.com/) - Very nice resources. A lot of utility when comparing with other methods.

## Author

- Website - On development... Still need to grasp more concepts
- Frontend Mentor - [@pcardas](https://www.frontendmentor.io/profile/pcardas)
- Twitter - [@pcardas](https://www.twitter.com/__pcardas__)
- Codewars - [@pcardas](https://www.codewars.com/users/__pcardas__)

# Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa).

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

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

## Screenshot

### The Desktop Size 1440px

![The Desktop Size 1440px](<images/127.0.0.1_5500_index.html%20(1).png>)

![The mobile Size 375px](</images/127.0.0.1_5500_index.html(iPhone%20SE).png>)

### Links

- Solution URL: [https://github.com/ankitwaware/Product-preview-card-component.git]()

- Live Site URL: [https://ankitwaware.github.io/Product-preview-card-component]()

## My process

1. Create Rough by Pen and PaperLayout
2. Used suitable HTML Element
3. Change CSS according to the design
4. Make it resonsive for small Screen size

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Desktop-first workflow

### What I learned

- The New HTML5 `<picture>` Element

```html
<picture class="image-box">
  <source media="(max-width:375px)" srcset="/images image-product-mobile.jpg" />
  <img
    class="image-big"
    srcset="/images/image-product-desktop.jpg"
    alt="Product"
  />
</picture>
```

- The overflow , Box-sizing , hover property

```css
.container {
  overflow: hidden;
}

* {
  box-sizing: border-box;
}

.button:hover {
  background-color: hsl(212, 21%, 14%);
}
```

### Continued development

- The responsiveness of the solution for the differnt type of screen and width.

### Useful resources

- [MDN Docs](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/picture) - This helped me for changing the image while making it responsive. I really liked this pattern and will use it going forward.

## Author

- Ankit Waware
- Frontend Mentor - [@ankitwawawre](https://www.frontendmentor.io/profile/ankitwaware)
- Twitter - [@wawareankit](https://www.twitter.com/wawareankit)

# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

# Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

## Overview

### The challenge

Create a blog preview card.

Users should be able to:

- See hover and focus states for all interactive elements on the page (title of the article)

### Screenshot

![](./images/screenshot.png)

### Links

- [Solution URL:](https://github.com/crolette/product-preview-card-component)
- [Live Site URL:](https://crolette.github.io/product-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties and nesting
- upload to Git directly via GitHub in VS Code

### What I learned

Improve my CSS nesting knowledge

```css
.product {
    [...]

    .product__price {
      display: flex;
      align-items: center;
      column-gap: 16px;

      & p:first-child {
        color: var(--cyan);
        font-size: 2.5em;
        font-family: "Fraunces", serif;
      }

      & p:last-child {
        text-decoration: line-through;
        color: var(--gray);
      }
    }
```

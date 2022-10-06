# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Frontend Mentor - Product preview card component solution](#frontend-mentor---product-preview-card-component-solution)
  - [Table of contents](#table-of-contents)
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

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![desktop preview screenshot](./screenshots/desktop-version.png)

### Links

- Solution URL: [github](https://github.com/alseny-diallo/preview-card)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [Sass](https://sass-lang.com/) - Css preprocessor

### What I learned

To see how you can add code snippets, see below:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="style.css" />
  <title>Document</title>
</head>
<body>
  <main class="grid">
    <div class="grid--item-one">1</div>
    <div class="grid--item-two">2</div>
    <div class="grid--item-three">3</div>
  </main>
</body>
</html>
```

```scss
$font-stack: Helvetica, sans-serif;
$primary-color: #333;

.grid {
  display: grid;
  gap: 2rem;
  grid-template-columns: repeat(3, 1fr);
  &--item-two{
    background-color:$primary-color;
    grid-column: 1/3;
    grid-row: 1/2;
  }
}
```

## Author

- github - [alseny-diallo](https://github.com/alseny-diallo)
- Twitter - [@alsenydiallo09](https://www.twitter.com/alsenydiallo09)

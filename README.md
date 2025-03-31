# Frontend Mentor - Recipe Page Solution

This is my solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help improve coding skills by building realistic projects.

## Table of Contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)
  - [Useful Resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The Challenge

Users should be able to view a recipe page with a clear layout, including ingredients, instructions, and nutritional information. The page should be responsive and accessible.

### Screenshot

![Recipe Page Screenshot](preview.jpg)

This screenshot shows my solution to the Recipe page challenge.

### Links

- Solution URL: [Solution on GitHub](https://github.com/V0000DY/recipe-page-main)
- Live Site URL: [Live Site](https://v0000dy.github.io/recipe-page-main/)

## My Process

### Built With

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I Learned

This project provided valuable experience in several key areas:

1. **Semantic HTML**:

- Utilized semantic elements like `<main>`, `<section>`, and `<article>` to improve the structure and accessibility of the HTML.

```html
<main>
  <article class="recipe">
    <section></section>
    <section></section>
    <!-- Recipe content -->
    <section></section>
    <section></section>
  </article>
</main>
```

2. **Responsive Design**:

Practiced creating responsive layouts using CSS media queries to ensure the page looks great on all devices.

```css
@media (max-width: 736px) {
  .recipe,
  .header img {
    border-radius: 0;
  }
}
```

3. **CSS Grid**:

Learned how to use CSS Grid for complex layouts, such as arranging ingredients and instructions in a grid format.

```css
.table {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  grid-template-rows: repeat(4, 2.875rem);
  margin: 1rem 0 2rem 0;
  align-items: center;
}
```

4. **CSS Custom Properties**:

Applied CSS custom properties to simplify color management and improve maintainability.

```css
:root {
  --white: hsl(0, 0%, 100%);
  --stone-100: hsl(30, 54%, 90%);
  --stone-150: hsl(30, 18%, 87%);
  --stone-600: hsl(30, 10%, 34%);
  --stone-900: hsl(24, 5%, 18%);
  --brown-800: hsl(14, 45%, 36%);
  --rose-800: hsl(332, 51%, 32%);
  --rose-50: hsl(330, 100%, 98%);
}
```

### Continued Development

In future projects, I aim to:

- Enhance my skills in using CSS Grid for more complex layouts.

- Focus on improving accessibility by implementing ARIA attributes and better semantic HTML.

- Explore using JavaScript for dynamic content updates and interactive elements.

### Useful Resources

[CSS-Tricks](https://css-tricks.com/): Flexbox Guide - Helped me understand flexbox properties better.

[MDN Web Docs](https://developer.mozilla.org/en-US/): Responsive Design Basics - A great resource for responsive design principles.

[Utopia](https://utopia.fyi/): A way of thinking about fluid responsive design.

### Author

- **Vitaly Rubtsov**
- Frontend Mentor: [@V0000DY](https://www.frontendmentor.io/profile/V0000DY)

## Acknowledgments

I want to thank the Frontend Mentor community for their support and feedback throughout this challenge. Special thanks to [Øystein Håberg](https://www.frontendmentor.io/profile/Islandstone89) that guided me through modern CSS responsive layouts.

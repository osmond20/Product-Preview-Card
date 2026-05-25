# Frontend Mentor - Product preview card component solution

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
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](screenshot/Screenshot_25-5-2026_164427_127.0.0.1.jpeg)

### Links

- Solution URL: [Frontend Mentor Solution](https://your-solution-url.com)
- Live Site URL: [Product Preview Card Website](https://osmond20.github.io/Product-Preview-Card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- SCSS for CSS styling

### What I learned

I learned how to use SCSS in this project and realized how useful, it is for my CSS styling workflow, as the CSS stylesheet gets larger, it really helped me alot and aided in reusing components. I also learned how to show different images based on different viewports offering flexibility and encourages responsive design.
Code snippets below:

```html
    <!--picture element used to embed multiple images of varying sizes for different screen sizes-->
    <picture>
            <source media="(min-width: 40rem)" srcset="images/image-product-desktop.jpg">
            <source media="(max-width: 40rem)" srcset="images/image-product-mobile.jpg">
            <img src="images/image-product-mobile.jpg" alt="Product advertised">
    </picture>
```
```scss
// creating scss variables
$font1: 'Montserrat', sans-serif;
$font2: 'Fraunces', sans-serif;
```

### Continued development

I will be focusing on responsive design and learning to blend grid and flexbox usages to ensure optimal responsive design for appropriate user interaction.

### Useful resources

- [Developer Mozilla](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/picture) - This helped use the picture element
- [SASS](https://sass-lang.com/guide/) - Really write in scss syntax and helped with my CSS styling immensely and I am grateful for the usefulness.

### AI Collaboration

Describe how you used AI tools (if any) during this project. This helps demonstrate your ability to work effectively with AI assistants.

- What tools did you use (e.g., ChatGPT, Claude, GitHub Copilot)? Github Copilot
- How did you use them? Used it as an agent to provide me hint whenever I got stuck and struggled with CSS styling, e.g, it was used to help figure out the border radius for the image and still have it fit the column on the grid child element that it was contained within.
- What worked well? It was useful as a guide providing me hints, gave me more space to think and actually solve the problem. Also it was useful for identifying css bugs that I may haev written and helped in making the code cleaner.
- What didn't? It is not useful when it writes all the code for me without it being read at least.

## Author

- Website - [Github](https://github.com/osmond20)
- Frontend Mentor - [@osmond20](https://www.frontendmentor.io/profile/osmond20)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

I am thankful to thecodercoder on her video of CSS grid and CSS flexbox, it was really helpful to learn the information from her video. And also kevin powell's video on focus states, it is a benefit to just refer to it whenever I would like to touch on reminder of what it is.


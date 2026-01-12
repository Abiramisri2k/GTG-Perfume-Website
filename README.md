# GTG Perfume - Home Page

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

A premium, high-conversion Home page for GTG Perfume. This project demonstrates advanced front-end capabilities, including a custom image gallery, interactive subscription models, and a responsive comparison system.

### Screenshot

![](./GTG%20Home%20page/assets/Desktop-view%20GTG%20perfume.png)

### Links

- [Live Site URL](https://gtg-perfume-website-three.vercel.app/)

## My process

### Built with

- **Semantic HTML5**: Used structured elements like `header`, `section`, `hgroup`, and `footer` for SEO and accessibility.
- **Modern CSS**:
  - CSS Custom Properties (Variables) for themed colors and consistent design tokens.
  - Flexbox and CSS Grid for complex layouts (like the Comparison Table and Subscription Cards).
  - Responsive layout using `clamp()` and `rem` units.
- **Vanilla JavaScript**:
  - Custom image carousel mapping logic.
  - Intersection Observer API for performance-focused scroll animations.
  - Accordion logic for the fragrance selection and collection sections.

### What I learned

During this project, I deepened my understanding of creating high-performance, responsive interfaces:

*   **Logic Mapping:** implemented a `thumbToImageMap` to bridge the gap between 8 UI thumbnails and 5 unique assets, ensuring a seamless user experience even with duplicate visual triggers.
*   **Mobile UX Polish:** Learned to handle mobile-specific browser behaviors, such as removing the `-webkit-tap-highlight-color` to provide a more app-like feel.
*   **Precision Layouts:** Mastered the alignment of absolute-positioned elements (arrows and dots) relative to responsive containers to ensure pixel-perfect vertical centering across all breakpoints.
*   **Performance Optimization:** Used `loading="lazy"` and optimized animation frames to ensure the page maintains high Core Web Vitals scores.

```css
/* Example of mobile-specific tap feedback removal */
* {
    -webkit-tap-highlight-color: transparent;
}
```

```javascript
/* Example of the mapping logic for the carousel */
const thumbToImageMap = [0, 1, 2, 3, 4, 1, 2, 3]; // Maps 8 thumbs to 5 images
```

## Author

- [Linkedin](www.linkedin.com/in/abiramisri)
- [Github](https://github.com/Abiramisri2k)

## Acknowledgments

Special thanks to **Cube.** for providing this assignment. It was a great opportunity to showcase my front-end development skills and attention to detail.
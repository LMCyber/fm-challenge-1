# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot - Desktop](#screenshots)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

This is my implementation of the ‘QR code component’ exercise, which involves creating a component with an image in the center and centering all the content.

### Screenshots

![](./images/desktop.png)
![](./images/mobile.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

The first step was to identify the HTML tags I needed to use, following proper semantics, and then position them in the correct place. After that, I proceeded to apply the formatting as indicated in the style guide provided to me. Finally, I dedicated myself to creating the media queries for different screen sizes.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

To see how you can add code snippets, see below:

```html
<main class="content">
  <div class="container">
    <div class="hero">
      <img src="images/image-qr-code.png" alt="QR Image" loading="lazy" />
      <h1>Improve your front-end skills by building projects</h1>
      <p>
        Scan the QR code to visit Frontend Mentor and take your coding skills to
        the next level
      </p>
    </div>
  </div>
</main>
```

```css
.container {
  background-color: var(--white);
  border-radius: 1.2rem;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding: 1rem;
  max-width: 90%;
  text-align: center;
}
```

## Author

- Website - [Luis Mendoza](https://github.com/LMCyber)
- Frontend Mentor - [@LMCyber](https://www.frontendmentor.io/profile/LMCyber)

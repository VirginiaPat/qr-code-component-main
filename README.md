# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

It is a simply and easy HTML and CSS challenge. The task was to create a QR code component

### Screenshot

![Screenshot of my solution](./ScreenshotSolution.png)

### Links

- Solution URL: [GitHub](https://github.com/VirginiaPat/qr-code-component-main.git)
- Live Site URL: [Netlify](https://qr-code-component-challenge-virgi.netlify.app)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I learned that it's a bad practise to use `html {font-size: 62.5%;}` to easily transform the px to rem. Instead I used the calc function. Once I learn Sass, I'll use the scss function:
@function rem($size) {
  $remSize: math.div($size, 16px);
@return #{$remSize}rem;
}

Also I used all the resets that are recommended for the global reset in css files, even though are not needed in this project

### Useful resources

- [A (more) Modern CSS Reset](https://piccalil.li/blog/a-more-modern-css-reset/) - This helped me with thw global reset

- [Should I change the default HTML font-size to 62.5%?](https://fedmentor.dev/posts/rem-html-font-size-hack/) - This is an amazing article which helped me finally understand why I shouldn't set font-size:62.5% in the html element.

## Author

- Frontend Mentor - [@VirginiaPat](https://www.frontendmentor.io/profile/VirginiaPat)
- Github - [VirginiaPat ](https://github.com/VirginiaPat)
- Netlify - [VirginiaPat](https://app.netlify.com/teams/virginia-patrika/sites)

## Acknowledgments

Many thanks to Øystein Håberg [@Islandstone89](https://www.frontendmentor.io/profile/Islandstone89) for his helpful feedback

# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- See hover states for interactive elements

### Screenshot

![](design/ScreenShot-2021-10-10.png)


### Links

- Solution URL: [Frontendmentor URL](https://www.frontendmentor.io/solutions/stats-preview-card-component-solution-with-html-and-css-c3N3s3mS5)
- Live Site URL: [Vercel deployed app](http://prj-02-stats-preview-card-component.vercel.app/)

## My process

### Built with

- HTML markup and plain CSS
- Google Fonts
- CSS variables
- Flexbox
- Mobile-first workflow

### What I learned

In this project I applied basic HTML and CSS concepts. The following snippets represent the principal topics learned and used:

How to apply filters to images in CSS3:
```css
.card img {
  max-width: 100%;
  filter: invert(11%) sepia(22%) saturate(918%) hue-rotate(220deg)
    brightness(70%) contrast(114%);
}
```
How to change opacity in hover state:
```css
.proceed-payment:hover {
  opacity: 0.5;
}
```
How to change the order of elements with Flexbox:
```css
  .card {
    display: flex;
    flex-wrap: nowrap;
    max-width: 90%;
  }
  .text-container {
    order: 1;
    flex: 0 1 50%;
    padding:initial;    
  }
  .image-container {
    order: 2;
    flex: 0 1 50%;
    padding: 0;
    margin: 0;
    overflow: hidden;
  }

```
How to adjust image size to parent container
```css
  .image-container img {
    width: 100%;
    max-height: auto;
    display: block;
  }
```

### Continued development

In the next projects I will continue using key concepts of HTML5 and CSS3. Also, my goal is to use a CSS framework like [TailwindCSS](https://tailwindcss.com/) and a new frontend development environment known as [Vite](https://vitejs.dev/).

### Useful resources

- [Fit images to container](https://developer.mozilla.org/es/docs/Web/CSS/object-fit) - The object-fit CSS property sets how the content of a replaced element, such as an <img> or <video>, should be resized to fit its container.

## Author

- Website - [Gustavo Sanchez](https://www.gusanche.dev)
- Frontend Mentor - [@gusanchedev](https://www.frontendmentor.io/profile/gusanchedev)
- Github - [@gusanchedev](https://www.github.com/gusanchedev)
- Twitter - [@gusanchedev](https://www.twitter.com/gusanchedev)
- Linkedin - [gusanchedev](https://www.linkedin.com/in/gusanchedev/)

## Acknowledgments

Thanks to Mariapaz for being my friend and support 💙

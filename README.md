# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./screenshot.png)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Github Pages](https://phemelo27.github.io/nft-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow
- Flexbox


### What I learned

I struggled a bit with the hover effect but this how I did it.

```html
<div class="img-container">
  <div class="hover-state">
      <div class="view-container"><img class="view" src="images/icon-view.svg" alt="">
      </div>
  </div>
</div>
```
```css
.view-container {
    /*  Layout  */
    display: flex;
    justify-content: center;
    align-items: center;

    /*  Styling */
    background-color: hsla(0, 0%, 0%, 0.1);
    border-radius: 10px;
    height: 100%;
    width: 100%;
    opacity: 0;
}

.view-container:hover {
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: hsla(178, 100%, 50%, 0.4);
    border-radius: 10px;
    height: 100%;
    opacity: 1;
}
```


### Continued development

- CSS Units
- CSS Naming Conventions

### Useful resources

- [MDN](https://developer.mozilla.org/en-US/) - This website contains a guide and reference section that covers a wide range of web related topics with in-depth explanations and easy to understand examples.
- [freeCodeCamp.org](https://www.freecodecamp.org/learn/) - Free online web development curriculum with a project-based learning approach. I'd recommend it to anyone still learning the basics of HTML and CSS.


## Author

- Website - [Phemelo Lekalakala](https://www.your-site.com)
- Frontend Mentor - [@Phemelo27](https://www.frontendmentor.io/profile/Phemelo27)
- Github - [@Phemelo27](https://github.com/Phemelo27/)


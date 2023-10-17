# Frontend Mentor - Loopstudios landing page solution

This is a solution to the [Loopstudios landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/loopstudios-landing-page-N88J5Onjw). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

#Desktop
![Screenshot 2023-10-17 at 12 25 35 PM](https://github.com/hashmi7917/loopstudios-landing-page/assets/38833326/026edba6-e9f1-4039-95bd-9727eb52ecb6)

#Mobile
![Screenshot 2023-10-17 at 12 28 14 PM](https://github.com/hashmi7917/loopstudios-landing-page/assets/38833326/78273c49-dd2f-4908-88b5-c35a60dab7e3)

### Links

- Solution URL: [GitHub](https://github.com/hashmi7917/loopstudios-landing-page)
- Live Site URL: [Netlify](https://loopstudios-landing-page-hashmi.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

layouts and responsiveness

To see how you can add code snippets, see below:

```html
<ul class="header__nav">
  <li><a class="cool-link">About</a></li>
  <li><a class="cool-link">Careers</a></li>
  <li><a class="cool-link">Events</a></li>
  <li><a class="cool-link">Products</a></li>
  <li><a class="cool-link">Support</a></li>
</ul>
```

```css
.header__nav {
  width: 34%;
  list-style: none;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
```

```js
function openNav() {
  document.getElementById("sidemenu").style.width = "100%";
}

function closeNav() {
  document.getElementById("sidemenu").style.width = "0";
}
```

### Continued development

CSS Grids

### Useful resources

- [MDN](https://developer.mozilla.org/en-US/) - This helped me for Background Image. I really liked this pattern and will use it going forward.

## Author

- Instagram - [Hashmi.Developer](https://www.instagram.com/hashmi.developer/)
- Frontend Mentor - [Muqtadeer](https://www.frontendmentor.io/profile/hashmi7917)
- GitHub - [hashmi7917](https://github.com/hashmi7917)

## Acknowledgments

MDN Resources.

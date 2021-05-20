# Frontend Mentor - Single price grid component solution



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

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [Styled Components](https://styled-components.com/) - For styles

### What I learned

Another project to familiarize myself with CSS grid and Flex-box. 

````css
@media (min-width: 768px) 
{
    .wrapper 
    {
        grid-template-columns: 1fr 1fr;
        grid-template-rows: 1fr 1fr;
        grid-template-areas: 
        "community community"
        "subscriptions why";
    }
    .community 
    {
        justify-content: center;
    }
    .subscription 
    {
        justify-content: center;
    }
    .why_us 
    {
        display: flex;
        flex-direction: column;
        justify-content: center;
    }
}
````



### Continued development

There still are some visual adjustments that need to be tweak. 

### Useful resources

- [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-template-areas) - Where I go for reference when I need to review CSS Grid
- [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox) - Where I go for reference when I need to review CSS Flex-box

****

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@T4R0TARO](https://www.frontendmentor.io/profile/T4R0TARO)
- Twitter - [@taro_code](https://twitter.com/taro_code)



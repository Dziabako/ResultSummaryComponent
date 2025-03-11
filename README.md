# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page
- **Bonus**: Use the local JSON data to dynamically populate the content

### Screenshot

![Screenshot](./screenshot.png)

### Links

- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process
1. At the beggining I added html tags and classes to the elements
2. Started working on each element starting from the biggest one ("container" class finishing on images)
3. Firstly I focues on desktop view
4. After finishing dektop view I started working on mobile view (still need to work on that more in the future projects)
5. After finishing all above I started to work on README.md

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Media Query

### What I learned

Basic layout using flexbox. Also (which was something new for me) media query. Previously I was using bootstrap for applying responsive layout but this time I prefered to do it without it (even when I was using GitHubCopilot to help me out). Below is my @media css code

```css
@media (max-width: 768px) {
    .container {
        padding: 20px;
    }

    .result-summary {
        flex-direction: column;
        width: 100%;;
    }

    .left-side, .right-side {
        width: 100%;
        height: 100%;
    }

    .left-side {
        margin-left: -21px;
        border-radius: 20px 20px 0 0;
    }

    .right-side {
        margin-left: -21px;
        border-radius: 0 0 20px 20px;
    }

    .score-medium {
        width: 35%;
    }

    .button {
        width: 97%;
        margin-top: 0.5rem;
        height: 2.5rem;
    }

    .attribution {
        display: none;
    }
}
```

### Continued development

Continue working on making more "pretty" css and html code, work more on new css possibilities, at some point also to start adding js and also some Python code (I am familiar with python-flask, flask-wtf, flask-login, flask-sqlalchemy)

### Useful resources

GitHub Copilot 

## Author

- Website - [@Dziabako](https://github.com/Dziabako)
- Frontend Mentor - [@Dziabako](https://www.frontendmentor.io/profile/Dziabako)


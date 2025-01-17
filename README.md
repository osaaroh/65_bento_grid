# Bento grid - Frontend Mentor - 

This is a solution to the [Bento grid challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj). 

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

- View the optimal layout for the interface depending on their device's screen size

### Screenshot

![](./screenshot.png)



### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid


### What I learned

- CSS grid-template-areas and grid-area

```css
.bento_grid {
  
  grid-template-areas:
    "scheduleQuicker hero hero schedule"
    "scheduleQuicker hero hero schedule"
    "scheduleQuicker multipleAccounts consistentPosting schedule"
    "aiwriting multipleAccounts consistentPosting schedule"
    "aiwriting fasterAudienceGrowth growFollowers growFollowers"
    "aiwriting fasterAudienceGrowth growFollowers growFollowers";
}

.bento_item_1 {
  grid-area: hero;
}

```

## Author

- Website - [Osaro Iyoha](https://osaro.vercel.app/)
- Frontend Mentor - [@osaaroh](https://www.frontendmentor.io/profile/osaaroh)


Check out [The Markdown Guide](https://www.markdownguide.org/) to learn more about markdown.



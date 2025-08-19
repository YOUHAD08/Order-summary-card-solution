# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj).

## Table of contents

- [Frontend Mentor - Order summary card solution](#frontend-mentor---order-summary-card-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
      - [Desktop view](#desktop-view)
      - [Mobile view](#mobile-view)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
    - [Author](#author)
    - [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements
- View the optimal layout depending on their device's screen size (mobile & desktop)

### Screenshot

#### Desktop view

![](design\desktop-design.jpg)

#### Mobile view

![](design\mobile-design.jpg)

### Links

- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Responsive design with media queries
- Mobile-first workflow

### What I learned

While building this project, I strengthened my understanding of **responsive design** and **media queries**.  
For example, adapting the card for different screen sizes using `@media` queries:

```css
@media (max-width: 500px) {
  .card-content {
    width: 320px;
    padding: 2.5rem;
  }
}
```

I also learned how to use CSS variables to make colors consistent and easy to update:

```css
:root {
  --blue-100: hsl(225, 100%, 94%);
  --blue-700: hsl(245, 75%, 52%);
}
```

### Continued development

In future projects, I want to focus on:

- Improving accessibility (keyboard navigation and ARIA roles)
- Experimenting with CSS animations for hover effects
- Practicing more on structuring components in a scalable way

### Author

- Frontend Mentor - [@AyoubYouhad](https://www.frontendmentor.io/profile/AyoubYouhad)
- GitHub - [@AyoubYouhad](https://github.com/YOUHAD08/Order-summary-card-solution.git)

### Acknowledgments

Thanks to the Frontend Mentor community for providing feedback and useful discussions that helped me improve this solution.

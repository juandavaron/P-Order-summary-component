- Live Site URL: [here](https://juandavaron.github.io/P-Order-summary-component/)

![screenshot](/assets/full-screenshot.png)

# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge
[Top](#table-of-contents)

Users should be able to:

- See hover states for interactive elements

### Screenshot
[Top](#table-of-contents)

![screenshot](/assets/full-screenshot.png)

### Links
[Top](#table-of-contents)


- Live Site URL: [here](https://juandavaron.github.io/P-Order-summary-component/)

## My process

### Built with
[Top](#table-of-contents)


- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [Sass](https://sass-lang.com/) - CSS Pre-processor


### What I learned
[Top](#table-of-contents)


For this project I started using the BEM methodology. It was helpful mixing it with the SASS pre-processor and it helped me to speed up the process.

```html
<div class="main__container">
  <div class="main__item"></div>
</div>
```
```scss
.main{
  &__container{
    display: flex;
    justify-content: center;
  }

  &__item{
    background-color: #fff;

    &:hover{
      background-color: #000
    }
  }
}
```

## Author
[Top](#table-of-contents)


- Linkedin - [Juan Varón](https://www.linkedin.com/in/juanvarong/)
- Twitter - [@nosoyesejuan_](https://www.twitter.com/nosoyesejuan_)
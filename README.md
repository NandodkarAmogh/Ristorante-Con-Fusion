# Restaurant Webpage

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)



## Overview

### Screenshot

![](./images/Animation.gif)
![](./images/img1_desktop.png)
![](./images/img1_mobile.png)
![](./images/img2_desktop.png)
![](./images/img2_mobile.png)
![](./images/img3_desktop.png)
![](./images/img3_mobile.png)
![](./images/img4_desktop.png)
![](./images/img4_mobile.png)

### Links

- Solution URL: [https://github.com/NandodkarAmogh/Vanilla-JavaScript-Todo-App](https://github.com/NandodkarAmogh/Vanilla-JavaScript-Todo-App)
- Live Site URL: [https://vanilla-javascript-todo-list.netlify.app/](https://vanilla-javascript-todo-list.netlify.app/)

## My process

### Built with

- CSS custom properties
- Flexbox
- Mobile-first workflow
- [JavaScript](https://www.javascript.com/)

### What I learned

This project helped me in revising some of the core javascript concepts like DOM manipulations and styling.

```js
const questions = document.querySelectorAll('.question');

questions.forEach((question) => {
    const btn = question.querySelector('.question-btn');
    btn.addEventListener('click', (e) => {
        //to close other questions while accessing one particular question
        questions.forEach((item) => {
            if(item !== question) {
                item.classList.remove('show-text')
            }
        })

        //toggling the show-hide functionality
        question.classList.toggle('show-text')
    })
})

```
## Author

- Github - [@NandodkarAmogh](https://github.com/NandodkarAmogh)






 

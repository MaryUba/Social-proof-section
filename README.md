# Frontend Mentor - Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the section depending on their device's screen size

### Screenshot

##### Desktop view

![screenshot](./image/desktop%20preview.png)
##### Mobile view
![screenshot](./image/mobile%20preview.png)


### Links

- [Live site URL](https://maryuba.github.io/Social-proof-section/)

## My process

### Built with

- HTML markup
- CSS custom properties
- Flexbox
- CSS Grid
- Desktop-first workflow
- [Font](https://fonts.google.com/specimen/League+Spartan) 


### What I learned

I used the translate property and assigning styles to specific child properties for the first time and although it was a bit challenging I was able to acheive a good result
Here's a snippet below:

```html
div class="card">
                        <div class="cardinfo">
                            <img class="userimg" src="./image/image-colton.jpg" alt="userimg">
                            <div class="">
                                <h2>Colton Smith </h2>
                                <h3>Verified Buyer</h3>
                            </div>
                        </div>
                        <p class="user-review">"We needed the same printed design as the one we had ordered a week prior.
                            Not only did they find the original order, but we also received it in time.
                            Excellent!"</p>
                    </div>
```
```css
.card:nth-child(2) {
    transform: translateY(1.5rem);
}
.card:nth-child(3) {
    transform: translateY(2.8rem);
}
```


### Useful resources

I got a lot of help from the Frontend mentor discord channel. I would advice to join their channel and consult the help section.

- [Discord join link](https://discord.gg/UAfh3qzhYb) - This helped me as I saw someone with my exact complaint who a commumity member had helped.

## Author

- Github - [@MaryUba](https://github.com/MaryUba)
- Frontend Mentor - [@MaryUba](https://www.frontendmentor.io/profile/MaryUba)


## Acknowledgments

I would like to thank my mentor at my web2 class I'm taking [Adetutu](https://github.com/Adetutu777) for her insight on this project.


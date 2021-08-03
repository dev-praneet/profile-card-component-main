# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

- Build out the project to the designs provided



### Links

- [Solution URL](https://github.com/geeky-amat/profile-card-component-main)
- [Live Site URL](https://geeky-amat.github.io/profile-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### What I learned

In doing this project some of the things that I learnt was that I could add more than one background images in any section. Also learnt that images are inline objects just like text and have previously defined padding-bottom even if we don't give it explicitly to take accomodate the descenders (eg. 'g', 'j', 'y' etc) . To get rid of the padding-bottom, some rules that could be used are

```css
.image-container {
  line-height: 0;
  font-size: 0;
}
```

or

```css
img {
  vertical-align: top;
}
```
or

```css
img {
  display: block;  /* display: inline-block; won't do the job */
}
```

Moreover, the image in .svg format doesn't seem to follow 'height' property in css exactly (rather it is more concerned about maintaining its original aspect ratio) if the units are in percentages but if it is in px units, it works fine. Same isn't the case with 'width'. Also, 'object-fit' property doesn't work with .svg images.


### Continued development


## Author

Geeky

## Acknowledgments

Mostly, I got my doubts cleared from youtube videos and stack exchanges Q&A

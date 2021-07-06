# Frontend Mentor - Fylo data storage component solution

This is a solution to the [Fylo data storage component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/fylo-data-storage-component-1dZPRbV5n). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)



## Overview
- Fylo data storage component
--It is a storage space.
--The interface shows a block which contains 3 options.
  1.Document option where user can upload their documents.
  2.Folder, where user can see his uploads.
  3.Upload, where user can upload their file for their drive or any other cloud storage.
--And the other block contains the progress bar which shows how much of the storage is used and how much is left.

### Screenshot

![Screenshot](images\Screenshot.png)
The easiest way of taking a screenshot for window user is just to press win+shift+s after that a drag pointer will appear and you can select the area you want to take the screenshot.
And you can also edit it or crop it.
Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

### Links

- Solution URL: [Solution](https://your-solution-url.com)
- Live Site URL: [live site](https://your-live-site-url.com)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

At first it seems how would I make a pointing arrow but after using pseudo selector ::before & ::after.


```css
.float-box::after{
    content:'';
    position:absolute;
    right:0px;
    top:45px;
    border-top:15px solid transparent;
    border-right:25px solid #ffff;
    border-left:none;
    border-bottom:25px solid transparent;
}

```

## Author

- Frontend Mentor - [@JakeCodes42](https://www.frontendmentor.io/profile/JakeCodes42)

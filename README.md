# Video Project

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


## Overview
Created a switch button for a video with JavaScript

### The challenge

Users should be able to:

-	Press the switch button to play or pause the video


### Screenshot

![](./screenshot.png)

### Links

- Solution URL: 
- Live Site URL: 

## My process
-	I followed along with the FreeCodeCamp Youtube tutorial to layout out my HTML, JS and CSS. 
- 	We added an overlay to our video container with CSS to dim the brightness of our video as well as add a better background for our header and button. We used the z-index to maneuver the placement of the video behind the overlay so we can still see our button and text.
-   We also have a preloader element here for our webpage that can been seen on the screen before the video loads. We programmed some JavaScript for this as well. 
-	The JavaScript for this file was pretty simple. We added some code that controls the behavior of a switch button and a video container. When the button is clicked, the code checks if it has the "slide" class. If it does not, it adds the class and pauses the video. If it has the class, it removes the class and plays the video.
-   We included an event listener for the "load" event on the window object. When the whole page, including all dependent resources such as stylesheets and images, has loaded, the "hide-preloader" class is added to the "preloader" element.
-   Afterwards, I added some text animation for my header using polygon clip paths and an infinite loop so it looks like a wave for my test and added some inset shadow to my button for more depth.  


### Built with

- HTML
- CSS 
- Javascript
- Responsive mobile & web design

### What I learned

-   This code is useful for controlling the behavior of a video player and creating a preloader for a webpage.

### Continued development
-	One thing I want to continue learning is repsonsive animations, I still struggle here a bit but I figure extra practice could resolve that. 


### Useful resources

- Free Code Camp Youtube tutorial- https://www.youtube.com/watch?v=3PHXvlpOkf4&t=11773s


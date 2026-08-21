# Frontend Mentor - Grid landing page solution

This is a solution to the [Grid landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/grid-landing-page). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the page depending on their device's screen size
- See hover and focus states for all interactive elements on the page
- Open and close the navigation menu at any screen size (optional JavaScript)

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [Add solution URL here](https://github.com/Daucko/frontend-mentor-grid-landing-page)
- Live Site URL: [Add live site URL here](https://frontend-mentor-grid-landing-page-six.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Javascript

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.
I used this project to refresh my knowledge of using fonts not built into VS code, like the fonts from google-fonts. This embedded into the project from the stylesheet as shown below:

```css
@font-face {
  font-family: 'Inter';
  src: url('/assets/fonts/inter/inter-variable.ttf');
}
```

I used this project to dig deep into grid layout. I also put to use the blending of my knowledge of Flexbox and Grid Layout. This was used in the stylesheet as shown below:

```css
body {
    ...;
  display: flex;
  flex-direction: column;
}
```

and

```css
main {
    ...;
  display: grid;
  grid-template-columns: 2fr 3fr;
}
```

I also put my javaScript knowledge to test. Although, I used just few lines, I was able to put functionality into the menu button using the javaScript Document Object Module(DOM) to target some classes as shown below:

```js
document.querySelector('.menu').style.display = 'none';
```

### Continued development

I want to focus my attention on how to master javascript concepts and also perfect 'Grid Layout'.

### Useful resources

- [Example resource 1](https://www.w3schools.com/js/js_htmldom_methods.asp) - This helped me to target the right css property using DOM.

### AI Collaboration

Since the project starter files has two files that instruct AI agents and Claude to not get involve in the execution of the project, the copilot in my VS Code was deactivated. But I made use of 'deepseek' in my browser when I got stuck on non alignment of the page components due to the footer floating on the aside components.

## Author

- Website - [Add your name here](https://www.daucode-portfolio.vercel.app)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/daucko)
- Twitter - [@yourusername](https://www.twitter.com/daucoooflife)

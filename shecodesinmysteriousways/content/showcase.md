---
title: "Showcase"
author: "Hello Robot"
date: "2023-03-23"
output:
  html_document:
    df_print: paged
---

## What will this website be about?

First, comes the maths,namely algebra, and how they relate to the code. Please, please don't run away. I promise it will not be that bad. Dirty secret time, in high school I sucked, I mean SUCKED at math. It was a real struggle,**Lots of frustration, a because there was no internet, and my undiagnosed learning disability**. So to demonstrate the algebra, I will do it in code as I go. That way you do not have to struggle with TI-8* whatever Texas Instrument calculator or HP with its reverse polish notation. And it kills two birds with one stone. But it will be written in R, R is a very good introductory language, because it was not written for computer science/engineering people. You will see what I mean as we go along.



```css
/* PostCSS code */

pre {
  background: #1a1a1d;
  padding: 20px;
  border-radius: 8px;
  font-size: 1rem;
  overflow: auto;

  @media (--phone) {
    white-space: pre-wrap;
    word-wrap: break-word;
  }

  code {
    background: none !important;
    color: #ccc;
    padding: 0;
    font-size: inherit;
  }
}
```

```js
// JS code

const menuTrigger = document.querySelector('.menu-trigger')
const menu = document.querySelector('.menu')
const mobileQuery = getComputedStyle(document.body).getPropertyValue('--phoneWidth')
const isMobile = () => window.matchMedia(mobileQuery).matches
const isMobileMenu = () => {
  menuTrigger.classList.toggle('hidden', !isMobile())
  menu.classList.toggle('hidden', isMobile())
}

isMobileMenu()

menuTrigger.addEventListener('click', () => menu.classList.toggle('hidden'))

window.addEventListener('resize', isMobileMenu)
```

```html
<!-- HTML code -->

<section id="main">
  <div>
   <h1 id="title">{{ .Title }}</h1>
    {{ range .Pages }}
      {{ .Render "summary"}}
    {{ end }}
  </div>
</section>
```

### Python

Second will be python, honestly I am not a big fan, at all. But I am catching on and this is a form of coding that will and cannot be ignored because it is everything and everywhere. I personally find the syntax hard to understand as I come from an R background, and the indentation is kind of stuff of nighmares because I love my brackets {} and parentheses (). Anyway, I will learni it along with Pytorch and Skct-learn. It will have a green banner so you have a visual cue for which language you are learning.

#### SQL

- Yes, SQL there is no reason not too. It is a very easy language to learn. 
However, that easiness comes at a price, because it is so easy it can fool you into thinking that your information pull is correct. However, 
when you are joining or counting information NULLs and other superfulous information can be lurking in the background and give erroneous results.
- I speak from experience with this and that can spell disaster. 
The banner will be purple.

####Machine Learning 
I know a few things about this and will include it as time permts. We will start with the basic linear regression, and go from their I will also incude behind the scenes account of what the functions are doing so you can see the bigger picture, (see what I did there). The banner will be yellow.

####CyberSecurity
Lastly, I will include cyber security. I am just starting in this field so I am as much a novice as anyone else. I will show you how it relates to biology and genetics. The banner will be grey.
# Responsive-Portfolio

## Overview

In this project, a portfolio is created which is an update of [Basic-Layout](https://drangus.herokuapp.com). 

## Introduction
This app applies a ton of material learned about: HTML/CSS, GitHub, Heroku and responsive design. It expresses a thorough knowledge of HTML/CSS which helps in the understanding of JavaScript, especially when it is used to manipulate web pages.

## Procedure

* Create a new GitHub repositories and name it Responsive-Portfolio.

* Clone the repository unto local computer.

* Copy the contents of Basic-Portfolio [Basic-Layout](https://drangus.herokuapp.com) and paste the mentioned files into Responsive-Portfolio.

* Exclude dot files (e.g .git, .gitignore) from the Basic-Portfolio repo.

* Inside the Responsive-Portfolio folder, find the style.css file (inside assets/css). At the bottom of styles.css write the media queries.

* Use three @media screen tags, each with one of these max-widths: 980px, 768px and 640px.

* 980px is used because we do not want any of the contents to be cut off. Since the desktop layout is about 960px wide, we do not want the media queries to kick in before our content gets cut off.

* 768px is about the width of a tablet and 640px is about the width of a phone in landscape

* Make the layout match the following screenshots:
  * index.html: 980px, 768px, 640px
  * portfolio.html: 980px, 768px, 640px
  * contact.html: 980px, 768px, 640px

* Make the position of the header static (the default positioning) when the screen is 640px wide. 

* This is because the header design takes up a lot of room; and we don't want it to stick to the top of a small screen and leave no room for the rest of our site.

* Include the viewport tag in all the html files, otherwise the media-queries won't function like we'd expect on mobile devices.

* Use the Chrome extensions Window Resizer and Browser Width to see the browser dimensions in Chrome.*

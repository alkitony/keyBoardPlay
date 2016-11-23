## keyBoardPlay
A Portfolio Piece: This site is a variation of the patatap.com site. The key board play site uses paperjs for graphics and animation and howler.js for sound play. The Key Board Play site was an exercise from the Web Developer Bootcamp class. By pressing keys "a" through "z" a circle will be displayed in a random location and a corresponding sound will play. The circle will slowly fade out.

## Install Procedures

1. Download/Clone the keyBoardPlay.html and sounds directory.
2. Open index.html in a browser.

**Note:** You must have an internet connection to run the site. This site uses paperjs and howler.js cdn libraries.

## Background

This site and code were developed as part of the [Udemy: The Web Developer Bootcamp](https://www.udemy.com/the-web-developer-bootcamp/) course.

**Author:** Tony Lanera

**Date:** Oct 11th, 2016

**Description**
This site is a variation of the patatap.com site. The key board play site uses paperjs for graphics and animation and howler.js for sound play. The Key Board Play site was an exercise from the Web Developer Bootcamp class. By pressing keys "a" through "z" a circle will be displayed in a random location and a corresponding sound will play. The circle will slowly fade out.
The KeyBoardPlay site displays circles in random location and plays a corresponding sound when pressing any key between "a" through "z". This sites uses paperjs for graphics and animation and howler.js for sound play. The site is a variation of the [patatap.com](http://patatap.com).


**Purpose:**

The purpose of the exercise was to become familiar with utilizing a graphical and sound library. For simplicity sake the css style and JS script is contained within the html file. This can be separated out into their respective files. However since the bulk of the effort is JS, it made sense to keep it in one file.

**Highlight:**   

The initial exercise had hard coded an object for each letter, which contained a sound and color for each letter between a to z. Based on lessons learned with OOP, I created a constructor function and programmatically created 26 objects.

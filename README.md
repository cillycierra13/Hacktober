# Hacktober
Commit things here for reasons.
Getting everyone coding for hacktober

@charset "utf-8";
@font-face {
    font-family: Champagne;
    src: url('cac_champagne.woff') format('woff'),
         url('cac_champagne.ttf') format('truetype');
}
@font-face {   font-family: Grunge;
    src: url('1942.woff') format('woff'),
         url('1942.ttf') format('truetype');
}
@font-face {    font-family: Dobkin;
    src: url('DobkinPlain.woff') format('woff'),
         url('DobkinPlain.ttf') format('truetype')
}
/*
   New Perspectives on HTML5 and CSS3, 7th Edition
   Tutorial 2
   Case Problem 1
   
   PHCT Typographic Style Sheet
   Author: CillyCierra13
   Date:   10-31-18
   
   Filename: ph_styles.css

*/


/* Structural Styles */
html {
    background-color: hsl(91, 8%, 56%);
}
body {
    background-color: hsl(58, 31%, 84%);
    font-family: 'Palatino Linotype', 'Book Antiqua', Palatino, serif;
}
header {
     background-color: black;
 }
p{
    margin: 0px;
    padding: 5px 25px 25px 25px;
}
body > p {
    font-size: 1.1em;
    text-align: center;
}
address {
    font-style: normal;
    font-size: 0.9em;
    text-align: center;
    padding-top: 10px;
    padding-bottom: 10px;
}

/* Navigation Styles */
nav a {
    padding-top: 10px;
    padding-bottom: 10px;
    font-family: 'Trebuchet MS', Helvetica, sans-serif;
}
nav a:link, nav:visited {
    color: white;
    text-decoration: none;
    background-color: hsla(0, 0%, 42%, 0.4);
}
nav a:hover, nav a:active {
    color: hsla(0, 0%, 100%, 0.7);
    background-color: hsla(0, 0%, 42%, 0.7);
}


/* Section Styles */
section.playbill h1 {
    font-size: 3em;
    font-weight: normal;
    margin: 0px;
    padding: 20px 0px 10px 20px;
}
section#play1 {
    background-color: hsl(240, 100%, 88%);
}
section#play1 h1 {
    font-family: Champagne, cursive;
}

section#play2 {
    background-color: hsl(25, 88%, 73%);
}
section#play2 h1 {
    font-family: Grunge, 'Times New Roman', Times, serif;
}

section#play3 {
    background-color: hsl(0, 100%, 75%);
}
section#play3 h1 {
    font-family: Impact, Charcoal, sans-serif;
}

section#play4 {
    background-color: hsl(296, 86%, 86%);
}
section#play4 h1 {
    font-family: Dobkin, cursive;
}

/* Description List Styles */

dt {
    font-size: 1.3em;
    font-weight: bold;
    color: hsla(0, 0%, 0%, 0.4);
}

dd {
    font-size: 1.3em;
    margin-left: 0px;
    margin-bottom: 10px;
}

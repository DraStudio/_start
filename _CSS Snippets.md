# CSS Snippets

## Comments

/* ----  ---- */

/* ---- Color Palette ---- */

/* ---- Structure ---- */

/* ---- Typography ---- */

/* ---- Iconography ---- */

/* ---- Navigation ---- */

/*
Theme Name: 	Avalanche
Theme URI: 	http://drastudio.com
Description: 	Codebase by Drastudio
Version: 		1.0
Author: 		Oscar Cortez
Author URI: 	http://drastudio.com
*/




## Typography

text-indent: 100%;
white-space: nowrap;
overflow: hidden;

@font-face {
font-family: 'FontName';
src: url('../fonts/FontName.eot');
src: url('../fonts/FontName.eot?iefix') format('embedded-opentype'),
url('../fonts/FontName.woff') format('woff'),
url('../fonts/FontName.ttf') format('truetype'),
url('../fonts/FontName.svg#FontName') format('svg');
font-weight: normal;
font-style: normal; }

Georgia, Times, "Times New Roman", serif

@import 'bourbon';




## Iconography
.icon { padding-left: 22px; background-position: left center; background-repeat: no-repeat; }

ul.icon { padding-left: 0; margin-left: 0; }

ul.icon li { list-style: none; padding-left: 20px; background-position: left center; background-repeat: no-repeat; }




## Miscellaneous

transition: all .5s;

.clear{clear: both; height: 0;}




## Media Queries

@media only screen and (max-width: 480px) {

}

@media all and (-webkit-min-device-pixel-ratio: 1.5) {
  
}




## Media Queries Set

/* Tablet Portrait size to Base 996px */
@media only screen and (min-width: 768px) and (max-width: 995px) {}

/* All Mobile Sizes */
@media only screen and (max-width: 767px) {}

/* Mobile Landscape Size to Tablet Portrait */
@media only screen and (min-width: 480px) and (max-width: 767px) {}

/* Mobile Portrait Size to Mobile Landscape Size */
@media only screen and (max-width: 479px) {}


***

/* More specific ideas, thanks: https://css-tricks.com/snippets/css/media-queries-for-standard-devices/ */

***


/* CSS Media Queries, thanks: https://www.w3schools.com/css/css_rwd_mediaqueries.asp */

/* Extra small devices (phones, 600px and down) */
@media only screen and (max-width: 600px) {...}

/* Small devices (portrait tablets and large phones, 600px and up) */
@media only screen and (min-width: 600px) {...}

/* Medium devices (landscape tablets, 768px and up) */
@media only screen and (min-width: 768px) {...}

/* Large devices (laptops/desktops, 992px and up) */
@media only screen and (min-width: 992px) {...}

/* Extra large devices (large laptops and desktops, 1200px and up) */
@media only screen and (min-width: 1200px) {...}
About Letter Drop (jQuery)
===========

Letter Drop is a jQuery plugin for a CSS based rain like animation effect for typography. The plugin takes the text string within the defined element as input & splits each letter out adding a random time delay to each character from 1.0 to 1.9 secondss before dropping & rotating the letters down like droplets of rain. Just like rain, it's different every time.

Features
===========
* Lightweight - weighing in at 1.25kb (uncompressed), 603 bytes (minified) & 375 bytes (gzipped)
* Unobtrusive - if letter drop conflicts with any of your existing code or plugins **I will personally buy you a beer!**
* Chains - compliments core & UI jQuery functions when writing in a chain e.g... .show().letterDrop().fadeOut(6000)
* Configurable - Letter Drop's custom rain animation can be fully manipulated, altered or replaced completely in the letter_drop.css file (bundled)

Dependancies
===========
1. jQuery 2.x or higher (untested on lower versions but should work)
2. letter_drop.css (bundled)

Usage
===========
$( 'selector' ).letterDrop();

Demo
===========
http://codepen.io/KryptoniteDove/pen/gipuw

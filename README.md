# Word Gen

A simple html page which generates words by smashing 2-5 letter scrabble words together.

BSD-2 license

## Usage
Clone via git
Deploy as a single page website or file:://open should work

Using URL parameters you can control the word generation:

## Examples
Generate words using 2-letter, 3-letter, and 5-letter lists:
 ../path/to/wordgen/index.html?use=2,3,5

Generate words by combining 3 random words:
 ../path/to/wordgen/index.htmlwordgen/index.html?wpw=3

Combining 3 words from the lists of 2 and 3 letter words:
../path/to/wordgen/index.htmlwordgen/index.html?wpw=3&use=2,3


## Building etc
There is no building or bundler - this is a static HTML project written with [bitwrench.js](https://github.com/deftio/bitwrench) and [Bootstrap](https://www.getbootstrap.com)
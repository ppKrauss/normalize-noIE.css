# normalize-noIE.css
This adaptation of `normalize.css` (cutting away ~1/3 of code by removing [IE](https://en.wikipedia.org/wiki/Internet_Explorer) support) can be used with [web applications](https://en.wikipedia.org/wiki/Web_application) optimized for non-MS browsers, or in production environments where the user has no option to use IE.

The  [original `normalize.css`](https://github.com/necolas/normalize.css) is a customisable CSS file that makes browsers render all
elements more consistently and in line with modern standards.

## Install

No other styles should come before Normalize.css.

It is recommended that you include the `normalize-noIE.css` file as untouched library code.

## What does it do?

* Preserves useful defaults, unlike many CSS resets.
* Normalizes styles for a wide range of elements.
* Corrects bugs and common browser inconsistencies.
* Improves usability with subtle improvements.
* Do nothing about IE: avoid to lost time and bandwidth with it.

## Browser support

* Google Chrome (latest)
* Mozilla Firefox (latest)
* Mozilla Firefox ESR
* Opera (latest)
* Apple Safari 6+

## CSS recommendations

* `input[type="checkbox"]` and  `input[type="radio"]`:  it's recommended that you don't attempt to style these elements. Firefox's implementation doesn't respect box-sizing, padding, or width.

* ...

## Acknowledgements

Original Normalize.css is a project by [Nicolas Gallagher](https://github.com/necolas),
co-created with [Jonathan Neal](https://github.com/jonathantneal).


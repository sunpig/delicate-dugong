# delicate-dugong
A front-end coding exercise.

## The brief
* [Description](https://sunpig.github.com/delicate-dugong/brief/brief.txt)
* [Reference screenshot](https://sunpig.github.com/delicate-dugong/brief/screenshot.png)

## Implementation notes
* Added responsive elements for small screens:
  * Horizontal tabs collapse into a single tab-shaped heading. Clicking the heading presents a vertical list of options.
  * "Weekly change" columns disappear for small screens, and the values are placed in the rates/apr columns.
* Vertical centering for the "Check rates in another area" form uses a silly conditional-comment table hack for IE6/7. There's a better way, but… <http://giveupandusetables.com/>

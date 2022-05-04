# positioning schemes
There are four common types of CSS positioning schemes:

Normal flow
Relative positioning
Absolute positioning
Fixed positioning

## Normal flow
is when the position: static
it is the default option

it is when they would just be seperated, not next to each other, taking up their own space, vertically


Normal flow is when you do nothing on a page layout (default layout of your browser). It takes the content in the order it is found in the HTML and stacks it, one element after the other one element right on top of another other. Block-level elements (heading, paragraphs, sectional elements e.g. div, article, section) take their own space in the document flow and are stacked one on top of another.

Inline elements (e.g. img, a,) appear inside the block-level elements and they stack themselves based on the flow of line boxes. Think of how the lines of a paragraph are stacked; this is essentially the flow of inline elements. That is, they are stacked as wide as they can.

## relative

it allows it to be next to other elements without stacking, one image can be next to each other

but the other elements, tho they are not in the relative positioning, will still stack underneat, the one that was moved will still have space there, where it should have been and the others will have moved down

Note that using this method creates a hole where the element would normally be found.

## Absolute

is the same as relative, but when the element is moved the other static elements shifts up so there is no hole where the image is left

these are really tricky to position

https://canvas.sydney.edu.au/courses/38329/pages/css-position-schemes-absolute?module_item_id=1370126


## fixed
this will keep the position there constantly, even when scrolling, its overlayed on the top of other elements

# stacking

every element has a z axis, as in, you can control which layers are stacked on top of each otehr

they can overlap, and control which ones are in front and behind

by default they are all on the same plane

# floats

floats essentially gives it a higher axis and move it to whatever position you want

## clear

clear puts the element in the style to the very bottom and tells it that anything past that last element should go back to default underneat

https://canvas.sydney.edu.au/courses/38329/pages/css-semantics-exercise?module_item_id=1370133
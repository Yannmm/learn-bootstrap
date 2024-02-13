> You can find the shorthand notation explained at https://getbootstrap.com/docs/5.3/utilities/spacing/

> sometimes I prefer to read the documentaion chapter by chapter. It gives me a feeling that I'm learning something systematically. And it's good.


col-{breakpoint}-count, the {breakpoint} is based on `min-width` media queries. This means it will affect that breakpoint and all those above it. e.g., .col-sm-4 applies to sm, md, lg, xl, and xxl

- in the grid system, if you omit col-* for an element, then it default to `.col-12`, which is different from `.col`


# Column

- container -> row -> column -> content
- for `order-*`, ascending to display. If no order applied, then shift the head of queue.


- a reference to containing block: https://developer.mozilla.org/en-US/docs/Web/CSS/Containing_block

I wonder why CSS is so complicated. Maybe because it has a long history for web, compared with ohter platforms.


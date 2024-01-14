# svg_test_card
An svg image reproduction of Philips PM5544 television station color test card.

![reproduced PM5544 test card image](./pm5544.svg)

## Why

This was a hobby project. I did not find any good quality reproduction so I created one.

## Source of information

This reproduction is mainly based on the information in the Wikipedia article 
[Philips circle pattern](https://en.wikipedia.org/w/index.php?title=Philips_circle_pattern&oldid=1193634971).

## Challenges

1. **Sine wave patterns below the middle of circle**
   - SVG does not support gradients based on arbitrary functions.
   - Positioning and transforming patterns in SVG is quite cumbersome.

2. **Colors of the side color bars**
   - Color models are complex.
   - Interpretation of color information in the Wikipedia article was difficult.

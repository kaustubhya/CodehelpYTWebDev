flex makes the main container into flexbox.
The default direction is row.
We can set the direction of it using flex-direction: row or 
flex-direction: column

if we do flex-direction: row-reverse, then 
123 gets ordered into 321

flex-direction: column-reverse

gives
1
2
3

to 

3
2
1


flex-warp: It is adjusted to screen width without scrolling or changing the size

If something is to wide for one line for a screen, it comes to next line and keeps doing till the screen allows it to. Then it starts shrinking.
[see 16:00 in video](https://www.youtube.com/watch?v=tN12g5QUIqg&list=PLDzeHZWIZsTo0wSBcg4-NMIbC0L8evLrD&index=20)

flex-wrap properties:
- nowrap
- wrap reverse
- wrap


Flex Flow:
The flex-flow CSS shorthand property specifies the direction of a flex container, as well as its wrapping behavior.
[flex flow docs link] (https://developer.mozilla.org/en-US/docs/Web/CSS/flex-flow)


Justify content:
Places items according to the main axis

- if flex direction is row, main axis is horizontal

- if flex direction is column, main axis is vertical
[read here](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-content)

Align items:
This places content along cross axis

- if flex direction is row, cross axis is vertical

- if flex direction is column, cross axis is horizontal

[read here](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_flexible_box_layout/Aligning_items_in_a_flex_container)

align content: takes care of spacing between child elements
[Read here] (https://developer.mozilla.org/en-US/docs/Web/CSS/align-content)

flexbox done


Now let us talk about flex items

Flex items are the items inside the flexbox

order property:
used to change the sequence of flex items

[Read here](https://developer.mozilla.org/en-US/docs/Web/CSS/order)


Grow and Shrink
Let us say for box 1
flex-shrink: 4

Then box 1 will shink with 4x speed as compared to other boxes when screen size is reduced

Let us say for box 1
flex-grow: 4

Then box 1 will grow with 4x speed as compared to other boxes when screen size is increased

Also if you select flex-grow: 1 for all items, then they will occupy any space left in the screen for their div.
[see 36.00](https://www.youtube.com/watch?v=tN12g5QUIqg&list=PLDzeHZWIZsTo0wSBcg4-NMIbC0L8evLrD&index=20)

Flex Basis: Used to set initial dimensions of a flex item

[Read here](https://developer.mozilla.org/en-US/docs/Web/CSS/flex-basis)

Shorthand notation:

"flex(grow, shrink, basis)"

Align self:
Aligns individual items over cross axis
[Read](https://developer.mozilla.org/en-US/docs/Web/CSS/align-self)

Similarly we have justify self 
[Read](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-self)
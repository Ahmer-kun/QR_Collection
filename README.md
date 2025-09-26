

Cheatsheet Query @media 
https://gist.github.com/bartholomej/8415655

https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/CSS_layout/Media_queries

AISDE  tag


An <aside> element does not automatically shift left or right; by default, it acts as a block-level element and stacks with other content. You must use CSS, typically with the float property
(e.g., float: left; or float: right;), to move it to the left or right of the surrounding content. 

Default Behavior
Block-level Element:
The <aside> element behaves like a block, meaning it takes up the full width available and appears on its own line, pushing content above and below it. 
How to Shift Left or Right

Use the float Property: To position an <aside> element as a sidebar or to the side of other content, you apply CSS styling.
To float it to the left: aside { float: left; }.
To float it to the right: aside { float: right; }.

Adjust with Other CSS Properties:
width: You might set a specific width for the aside.
margin: Add a margin to create space around the floated element.
**display: flex;**: Modern layout techniques, like using display: flex` on a parent container, can also be used to arrange elements side-by-side. 

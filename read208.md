
# Class 08 Notes

## [Learn CSS-Flexbox](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox)

1. Flexbox is designed for one-dimensional content. Explain what this means.
- Flexbox is a one-dimensional layout method for arranging items in rows or columns. Items flex (expand) to fill additional space or shrink to fit into smaller spaces. This article explains all the fundamentals.

2. Explain the difference between the main axis and cross axis.
- main = side to side. The main axis is the axis running in the direction the flex items are laid out in (for example, as rows across the page, or columns down the page.) The start and end of this axis are called the main start and main end.
- cross = up and down. The cross axis is the axis running perpendicular to the direction the flex items are laid out in. The start and end of this axis are called the cross start and cross end.

3. How can using certain properties of flexbox negatively impact accessibility?
- we can use `warp` so the children dont break out of the container
- `flex-direction` and `flex-warp` can be shortened to `flex-flow`


## [Learn CSS-Layout](https://web.dev/learn/css/layout/)

1. What are some advantages of using flexbox over float?
-  Using floats we are limited to place items left or right but using flexbox we can modify our models in all four directions. Flexbox is a new concept 
-  Positioning child elements becomes easier with flexbox.
-  Flexbox is responsive and mobile-friendly.
-  Flex container’s margins do not collapse with the margins of its content.
-  We can easily change the order of elements on our webpage without even making changes in HTML.
-  
-  FLOAT = Float is a positioning layout model.
Float only focus on how an element or item can float inside a container.
Float can only place items on the right side or on the left side of the corresponding container.
Float has no effect if the display is absolute.
Float is best for small layout positioning.
There are some properties of floats such as `float:right, float:left, float:none, float:inherit, float:inline-start, float:inline-end, float:initial, float:unset`

2. How does this topic connect with your long term goals?
- becuase `flex` is a newer concept according to the readings, I feel like this will be the way forward. I think this will be used a lot in the projects we create here, and seems like a decent way in which to design your "boxes"


# Class 04

## Learn HTML

[Creating Hyperlinks](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks)

1. To create a basic link, we wrap text or other content inside what element?
Inside an `<a>` element using the `href` attribute

2. The `href` attribute contains what information?
Hypertext Reference, the Target, contains the web address

3. What are some ways we can ensure links on our pages are accessible to all
readers?
- Use clear link wording
- Don't repeat the URL as part of the link text
- Don't say "link" or "links to" in the link text
- Keep your link text as short as possible
- Minimize instances where multiple copies of the same text are linked to different places.

##CSS Layout

[CSS Layout Normal Flow](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Normal_Flow)
[CSS Layout: Positioning](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Positioning)

1. What is meant by “normal flow”?
Normal Flow, or Flow Layout, is the way that Block and Inline elements are displayed on a page before any changes are made to their layout. The flow is essentially a set of things that are all working together and know about each other in your layout. Once something is taken out of flow it works independently.

2. What are a few differences between `block-level` and `inline` elements?
- block level element's content fills the available inline space of the parent element containing it and grows along the block dimension to accommodate its content
- The size of Inline elements is just the size of their content. You can't set width or height on inline elements — they just sit inside the content of block level elements. If you want to control the size of an inline element in this manner, you need to set it to behave like a block level element
-Block Elements occupy the full width irrespective of their sufficiency. Inline elements don't start in a new line. Block elements always start in a line. Inline elements allow other inline elements to sit behind


3. ___ positioning is the default for every html element.
STATIC

4. Name a few advantages to using absolute positioning on an element.
it sits on its own layer separate from everything else. This is very useful: it means that we can create isolated UI features that don't interfere with the layout of other elements on the page. For example, popup information boxes, control menus, rollover panels, UI features that can be dragged and dropped anywhere on the page, and so on.

5. What is a key difference between fixed positioning and absolute positioning?
Absolutely positioned elements are positioned with respect to a containing block, which is the nearest positioned ancestor. If there is no positioned ancestor, the viewport will be the containing block. Elements with fixed positioning are fixed with respect to the viewport—the viewport is always their containing block. This means that you can create useful UI items that are fixed in place, like persistent navigation menus that are always visible no matter how much the page scrolls.

##Learn JS
[Functions - Reusable Blocks of Code](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Functions)

1. Describe the difference between a function declaration and a function invocation.


2. What is the difference between a parameter and an argument?


# Class 03

## Learn HTML
### [Ordered](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol) and [Unorderd](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul) Lists
1. When should you use an `unordered list` in your HTML document?
for grouping a collection of items that do not have a numerical ordering, and their order in the list is meaningless

2. How do you change the `bullet style` of unordered list items?
This attribute sets the bullet style for the list. Circle / disc / square
If not present and if no CSS list-style-type property applies to the element, the user agent selects a bullet type depending on the nesting level of the list.

3. When should you use an `ordered list` vs an `unorder list` in your HTML document?
Used to create a list of related items, in no particular order. Ordered list — Used to create a list of related items, in a specific order.

4. Describe two ways you can change the numbers on `list items` provided by an `ordered list`?
type="1" // type="I" // type="i"

## Learn CSS
[Box Model](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model)

1. Describe the CSS properties of `margin` and `padding` as characters in a story. What is their role in a story titled: “The Box Model”?
Padding is the bubble wrap in a box, around the content, up until the box/boarder. And margin is the space around the box and the delivery truck

2. List and describe the four parts of an HTML elements box as referred to by the `box model`.
- height&width =
- padding = The padding sits between the border and the content area and is used to push the content away from the border // cannot have negative
- border = The border is drawn between the margin and the padding of a box.
- margin = The margin is an invisible space around your box // can have negative

## Learn JS
### [ Arrays. Operators and Expressions. Conditionals. Loops.]

1. What data types can you store inside of an Array?
values that are simple reals or integers, vectors, matrices, or other arrays. Arrays are the only way to store sequences of integers, and some functions in Stan, such as discrete distributions, require integer arguments.

2.  Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?
Yes.  Console.log(people) // Console.log(people[#])

3. List five shorthand operators for assignment in javascript and describe what they do.
Assignment                    // x = f() // x = f()
Addition assignment  // x += f() // x = x + f()
Multiplication assignment // x *= f() // x = x * f()
Left shift assignment  // x <<= f() // x = x << f()
Logical AND assignment  // x &&= f() // x && (x = f())

4. Read the code below and evaluate the last expression and explain what the result would be and why.\
the result is 10dog because false is null/zero

5. Describe a real world example of when a conditional statement should be used in a JavaScript program.
checking authentication on a webpage

6. Give an example of when a Loop is useful in JavaScript.
Loops allows to run a code block multiple times without having to repeat it each time.

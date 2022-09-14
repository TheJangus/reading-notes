
[HTML Text Fundamentals](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/HTML_text_fundamentals)

[HTML Advanced Text Formatting](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Advanced_text_formatting)


1. Why is it important to use semantic elements in our HTML?
Writing semantic HTML makes your code easier to understand, making the
source code more readable for other developers. Screen readers and browsers
can interpret Semantic HTML better, which makes it more accessible

2. How many levels of headings are there in HTML?
H1-h6

3. What are some uses for the <sup> and <sub> elements?
you cannot use them both at the same time and you need to use MathML to
produce both a superscript and a subscript next to the chemical symbol of an
element, representing its atomic number and its nuclear number.
* The <sup> HTML element specifies inline text which is to be displayed as
superscript for solely typographical reasons. Superscripts are usually
rendered with a raised baseline using smaller text.g its atomic number and
its nuclear number.
The <sup> element should only be used for typographical reasons-that is, to
change the position of the text to comply with typographical conventions or
standards, rather than solely for presentation or appearance purposes.
Displaying exponents //  Displaying superior lettering //  representing
ordinal numbers, such as 4th

*The <sub> HTML element specifies inline text which should be displayed as
subscript for solely typographical reasons. Subscripts are typically
rendered with a lowered baseline using smaller text.
Marking up footnote numbers // Marking up the subscript in mathematical
variable numbers // Denoting the number of atoms of a given element within a
chemical formula = c6 h12 o6


4. When using the <abbr> element, what attribute must be added to provide
the full expansion of the term?
Adding a title attribute lets you provide an expansion or definition for the abbreviation or acronym.




[How CSS Is Structured](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/How_CSS_is_structured)

1. What are ways we can apply CSS to our HTML?
with an external stylesheet, with an internal stylesheet, and with inline styles.

2. Why should we avoid using inline styles?
least efficient implementation of CSS for maintenance. One styling change might require multiple edits within a single web page. Second, inline CSS also mixes (CSS) presentational code with HTML and content, making everything more difficult to read and understand. Separating code and content makes maintenance easier for all who work on the website.

3. Review the block of code below and answer the following questions:
3a. What is representing the selector?
 A rule for h2
3b. Which components are the CSS declarations?
Property & value = Color: black // padding: 5px
3c. Which components are considered properties?
Color & padding

[JavaScript Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)

1. What data type is a sequence of text enclosed in single quote marks?
A string
2. List 4 types of JavaScript operators.
Addition, assignment, strict equality, not/does not equal
3. Describe a real world Problem you could solve with a Function.
Can make a function for an alert for a timer


[Conditionals](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals)

1. An if statement checks a __ and if it evaluates to ___, then the code block will execute.
true

2. What is the use of an `else if`?
to specify a new condition to test, if the first condition is false

3. List 3 different types of comparison operators.
`>, <, >=, <=, ===, !==`

4. What is the difference between the logical operator `&&` and `||`?
`&&`  - (and) — This operator will be truthy (act like true) if and only if the expressions on both sides of it are true.
 `||` - (or) — This operator will be truthy if the expression on either side of it is true. Otherwise, it will be falsy (act like false).

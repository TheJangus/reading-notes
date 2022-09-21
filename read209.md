# Reading 09

## Forms and JS Events

### [Your First Form](https://developer.mozilla.org/en-US/docs/Learn/Forms/Your_first_form)

### [How to Structure a Web Form](https://developer.mozilla.org/en-US/docs/Learn/Forms/How_to_structure_a_web_form)

1. Why are forms so important in web development?
-Web forms are one of the main points of interaction between a user and a web site or application. Forms allow users to enter data, which is generally sent to a web server for processing and storage, or used on the client-side to immediately update the interface in some way (for example, add another item to a list, or show or hide a UI feature).

2. When designing a form, what are some key things to keep in mind when it comes to user experience?
- Order the Form Logically and Only Ask What’s Required
- Present Fields in a Single Column Layout
- Minimize the Number of Input Fields and User Typing Effort
- Match Fields to the Size of the Input
- Place Labels Above the Corresponding Input Felds
- Use Forgiving Formatting
- Don’t Use Placeholder Text as Input Field Label
- Distinguish Optional And Required Fields
- Avoid ‘Reset’ Button

3. List 5 form elements and explain their importance.
- The `<fieldset>` element is a convenient way to create groups of widgets that share the same purpose, for styling and semantic purposes. You can label a `<fieldset>` by including a `<legend>` element just below the opening `<fieldset>` tag
- The `<label>` element is the formal way to define a label for an HTML form widget. This is the most important element if you want to build accessible forms — when implemented properly, screen readers will speak a form element's label along with any related instructions, as well as it being useful for sighted users
- it's common practice to wrap a label and its widget with a `<li>` element within a `<ul>` or `<ol>` list. `<p>` and `<div>` elements are also commonly used. Lists are recommended for structuring multiple checkboxes or radio buttons.
- In addition to the `<fieldset>` element, it's also common practice to use HTML titles (e.g. `<h1>`, `<h2>`) and sectioning (e.g. `<section>`) to structure complex forms.


### [Introduction to Events](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events)

1. How would you describe events to a non-technical friend?
- Events are actions or occurrences that happen in the system you are programming, which the system tells you about so your code can react to them.  For example, if the user clicks a button on a webpage, you might want to react to that action by displaying an information box.

2. When using the addEventListener() method, what 2 arguments will you need to provide?
- the name of the event (the name of the event we want to register this handler for)
- a function to handle the event (the code that comprises the handler function we want to run in response to it.)

3. Describe the event object. Why is the target within the event object useful?
- it is automatically passed to event handlers to provide extra features and information
- The target event property returns the element that triggered the event. The target property gets the element on which the event originally occurred, opposed to the currentTarget property, which always refers to the element whose event listener triggered the event.


4. What is the difference between event bubbling and event capturing?
- With bubbling, the event is first captured and handled by the innermost element and then propagated to outer elements. With capturing, the event is first captured by the outermost element and propagated to the inner elements.
- Event capturing is the event starts from top element to the target element. It is the opposite of Event bubbling, which starts from target element to the top element.


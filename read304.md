## [React Docs - Forms](https://reactjs.org/docs/forms.html)

1. What is a ‘Controlled Component’?
-Controlled Components are those in which form's data is handled by the component's state. It takes its current value through props and makes changes through callbacks like onClick, onChange, etc.

2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
- As soon as they enter them
- instant input validation: we can give the user instant feedback without having to wait for them to submit the form (e.g. if their password is not complex enough)
- instant input formatting: we can add proper separators to currency inputs, or grouping to phone numbers on the fly
- conditionally disable form submission: we can enable the submit button after certain criteria are met (e.g. the user consented to the terms and conditions)
- dynamically generate new inputs: we can add additional inputs to a form based on the user’s previous input (e.g. adding details of additional people on a hotel booking)

3. How do we target what the user is entering if we have an event handler on an input field?
- When you need to handle multiple controlled input elements, you can add a name attribute to each element and let the handler function choose what to do based on the value of event.target.name.

## [The Conditional (Ternary) Operator Explained](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)

1. Why would we use a ternary operator?
- Shorter. We can use the ternary operator in place of if-else conditions or even switch conditions using nested ternary operators. Although it follows the same algorithm as of if-else statement, the conditional operator takes less space and helps to write the if-else statements in the shortest way possible

2. Rewrite the following statement using a ternary statement:
- x===y ? 'true' : 'false';

## Bookmark and Review
[React Bootstrap - Forms](https://react-bootstrap.github.io/forms/overview/)
[React Docs - conditional rendering](https://reactjs.org/docs/conditional-rendering.html)

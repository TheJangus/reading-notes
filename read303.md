## [React Docs - lists and keys](https://reactjs.org/docs/lists-and-keys.html)

1.      What does .map() return?
- map() function returns a map object(which is an iterator) of the results after applying the given function to each item of a given iterable (list, tuple etc.)

2.      If I want to loop through an array and display each value in JSX, how do I do that in React?
- The map() method is the most commonly used function to iterate over an array of data in JSX. You can attach the map() method to the array and pass a callback function that gets called for each iteration. When rendering the User component, pass a unique value to the key prop.

3.      Each list item needs a unique ____.
- key

4.      What is the purpose of a key?
- Keys help React identify which items have changed, are added, or are removed. Keys should be given to the elements inside the array to give the elements a stable identity:

## [The Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

1.      What is the spread operator?
- the use of an ellipsis of three dots (…) to expand an iterable object into the list of arguments.

2.      List 4 things that the spread operator can do.
- Copying an array
- Concatenating or combining arrays
- Using Math functions
- Using an array as arguments
- Adding an item to a list
- Adding to state in React
- Combining objects
- Converting NodeList to an array

3.      Give an example of using the spread operator to combine two arrays.
-  https://gist.githubusercontent.com/djD-REK/a65209b29b59a5717f3c6ad2701e8f3a/raw/6b5f7d5314f3d12f91f2efcd7d930571ae23e556/Examples%20of%20using%20the%20spread%20operator.js

4.      Give an example of using the spread operator to add a new item to an array.
-  https://gist.github.com/djD-REK/fe282feb0b84a5f1a50fd0b2e7e5510e/raw/4f291907917d3cbd9cbfcd000a218dbda4f18274/Adding%20an%20item%20to%20a%20list.js

5.      Give an example of using the spread operator to combine two objects into one.
- https://gist.github.com/djD-REK/1995aa70063ce1cadc126ae523626e19/raw/4823db5f5f893af1848c03804f832340dd750fe0/Combining%20object%20properties%20and%20methods%20with%20spread%20operator.js


## Videos


## [How to Pass Functions Between Components](https://www.youtube.com/watch?v=c05OL7XbwXU)

1.      In the video, what is the first step that the developer does to pass functions between components?
- create the function where the state is located that we are going to change
- increment = (person) => {    --passing in a person
Let ppl = this.state.people.map( (p) => {
If(p.name === name){
p.count++;
}
Return p;

Map will create a brand new array to pass

2.      In your own words, what does the `increment` function do?
- it is a method to increase counters

3.      How can you pass a method from a parent component into a child component?
- This.increment - the function -- this.props.increment(this.props.name)
Pass it again to parent - pass it like a prop

4.      How does the child component invoke a method that was passed to it from a parent component?
- call the increment method - update state - passing name back to the increment at the top level - state change - cause a re-render - pass down in props


## Bookmark and Review


[React Tutorial through ‘Declaring a Winner’] (https://reactjs.org/tutorial/tutorial.html)


[React Docs - Lifting State Up] (https://reactjs.org/docs/lifting-state-up.html)

## [React lifecycle](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
- Render happens in the Render Phase and the componenetDidMount happens in the Commit Phase

2. What is the very first thing to happen in the lifecycle of React?
- The constructor for a React component is called before it is mounted - then Mounted Phase

3. Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates
- constructor // render // React Updates // componentDidMount // componentWillUnmount

4. What does componentDidMount do?
- This method is invoked immediately after a component is mounted. If you need to load anything using a network request or initialize the DOM, it should go here. This method is a good place to set up any subscriptions. If you do that, don’t forget to unsubscribe in componentWillUnmount().

## Videos
## [React State Vs Props](https://www.youtube.com/watch?v=IYvD9oBCuJI)

1. What types of things can you pass in the props?
- renderlike - display something to a user - props allow us to create dynamic components - things you want your function to initilize

2. What is the big difference between props and state?
- props = outside of a component - arguements to a function - renderlike - display something to a user
- state = inside of a component - props pass into, state inside

3. When do we re-render our application?
- when apps need updating/ off user inputs - when set state function is invoked

4. What are some examples of things that we could store in state?
- things needing constant updating - saving user info - counters

## Bookmark and Review
[React Docs - State and Lifecycle](https://reactjs.org/docs/state-and-lifecycle.html)
[React Docs - handling events](https://reactjs.org/docs/handling-events.html)
[React Tutorial through ‘Developer Tools’](https://reactjs.org/tutorial/tutorial.html)
[React Bootstrap Documentation](https://react-bootstrap.github.io/)
[Boootstrap Cheatsheet](https://getbootstrap.com/docs/5.0/examples/cheatsheet/)
[Bootstrap Shuffle - a class “sandbox”](https://bootstrapshuffle.com/classes)
[Netlify](https://www.netlify.com/)

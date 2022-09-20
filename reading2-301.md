# State and Props #

## It is important to learn about state and props because it gives us the ability to update UI's as the data we recieve changes. It allows for inheritence between parent and child elements and gives us the flexibility to control what inherits traits from their parent elements ##

### *Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?* ###

- From the diagram it looks like the componentDidMount happens before the render occurs

### *What is the very first thing to happen in the lifecycle of React?* ###

- When an instance of a component is being created and inserted into the DOM it occurs during the mounting phase. Constructor, static getDerivedStateFromProps, render, componentDidMount, and UNSAFE_componentWillMount all occur in this order during mounting

### *Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates* ###

- constructor
- React Updates
- Render
- componentDidMount
- componentWillUnmount

### *What does componentDidMount do?* ###

- This method is invoked immediately after a component is mounted. If you need to load anything using a network request or initialize the DOM, it should go here. This method is a good place to set up any subscriptions. If you do that, don’t forget to unsubscribe in componentWillUnmount().

setState() can be called here, but it should be used sparingly, because it will cause a rerender, which can lead to perfomance issues

### *What types of things can you pass in the props?* ###

- Things you would pass into a function, what you want to initialize your component to

### *What is the big difference between props and state?* ###

- State as opposed to props is something that is inside the component. Props you pass into a commponent while state is already inside the component 

### *When do we re-render our application?* ###

- When you change the state inside your component it will re-render your application

### *What are some examples of things that we could store in state?* ###

- You can initialize a count by passing it as a prop, but it updates via state. Create dynamic elements within our application, if you want the title or description to change based on user input you would store it in state

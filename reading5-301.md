# Thinking in React #

## - ##

### *What is the single responsibility principle and how does it apply to components?* ###

- a component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents

### *What does it mean to build a ‘static’ version of your application?* ###

- To build a static version of your app that renders your data model, you’ll want to build components that reuse other components and pass data using props. props are a way of passing data from parent to child. If you’re familiar with the concept of state, don’t use state at all to build this static version. State is reserved only for interactivity, that is, data that changes over time. Since this is a static version of the app, you don’t need it

### *Once you have a static application, what do you need to add?* ###

- To build your app correctly, you first need to think of the minimal set of mutable state that your app needs. The key here is DRY: Don’t Repeat Yourself. Figure out the absolute minimal representation of the state your application needs and compute everything else you need on-demand

### *What are the three questions you can ask to determine if something is state?* ###

- Is it passed in from a parent via props? If so, it probably isn’t state.
- Does it remain unchanged over time? If so, it probably isn’t state.
- Can you compute it based on any other state or props in your component? If so, it isn’t state

### *How can you identify where state needs to live?* ###

- Identify every component that renders something based on that state.
- Find a common owner component (a single component above all the components that need the state in the hierarchy).
- Either the common owner or another component higher up in the hierarchy should own the state.
- If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and  add it somewhere in the hierarchy above the common owner component

### *What is a “higher-order function”?* ###

- Higher-order functions allow us to abstract over actions, not just values. They come in several forms. For example, we can have functions that create new functions

### *Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?* ###

- It sets up the expression to check if a number is n is greater than m

### *Explain how either map or reduce operates, with regards to higher-order functions* ###

- The higher-order operation that represents this pattern is called reduce (sometimes also called fold). It builds a value by repeatedly taking a single element from the array and combining it with the current value. When summing numbers, you’d start with the number zero and, for each element, add that to the sum

- The parameters to reduce are, apart from the array, a combining function and a start value. This function is a little less straightforward than filter and map

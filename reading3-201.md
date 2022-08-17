# Reading 3 #

## Learning about various uses of HTML, CSS, and JS gives us more flexibility and utility when designing pages. An array allows you to store different types of data such as strings and numbers making it a useful tool when using this JS ##

### *When should you use an unordered list in your HTML document?* ###

- The < ul > element is for grouping a collection of items that do not have a numerical ordering, and their order in the list is meaningless. Typically, unordered-list items are displayed with a bullet

### *How do you change the bullet style of unordered list items?* ###

- The bullet style is not defined in the HTML description of the page, but in its associated CSS, using the list-style-type property

### *When should you use an ordered list vs an unorder list in your HTML document?* ###

- The < ol > and < ul > elements both represent a list of items. They differ in that, with the < ol > element, the order is meaningful. To determine which one to use, try changing the order of the list items; if the meaning is changed, the < ol > element should be used, otherwise you can use < ul >

### *Describe two ways you can change the numbers on list items provided by an ordered list?* ###

- a for lowercase letters

- i for lowercase Roman numerals

### *Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?* ###

- The margin is an invisible space around your box. It pushes other elements away from the box. Margins can have positive or negative values. Setting a negative margin on one side of your box can cause it to overlap other things on the page. Whether you are using the standard or alternative box model, the margin is always added after the size of the visible box has been calculated

- The padding sits between the border and the content area and is used to push the content away from the border. Unlike margins, you cannot have a negative padding. Any background applied to your element will display behind the padding

### *List and describe the four parts of an HTML elements box as referred to by the box model* ###

- Some HTML elements, such as < a> , < span >, < em > and < strong > use inline as their outer display type by default

### *What data types can you store inside of an Array?* ###

- In the above example, each item is a string, but in an array we can store various data types — strings, numbers, objects, and even other arrays

### *Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?* ###

- It is a valid array because you can have an array within an array, you can also have multiple data types within the array. You would just have to console.log the name of the array to obtain the list of values within the array

### *List five shorthand operators for assignment in javascript and describe what they do* ###

-Assignment: x = f() means x = f()
Addition assignment: x += f() means x = x + f()
Subtraction assignment: x -= f() means x = x - f()
Multiplication assignment: x *= f() means x = x* f()
Division assignment: x /= f() means x = x / f()

### *ead the code below and evaluate the last expression and explain what the result would be and why* ###

-It would not evaluate because false is boolean and the addition operator would not work for it

### *Describe a real world example of when a conditional statement should be used in a JavaScript program* ###

- If you were askig a question and wanted different responses for different answers, for example if you wanted someone to guess a number between 1 and 10 and wanted to give them hints based on their answer. A conditional statement would work well for that

### *Give an example of when a Loop is useful in JavaScript* ###

- If you want to make sure someone acknowledges a user agreement you can make it so the prompt loops until the click yes

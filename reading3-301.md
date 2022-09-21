# Reading 3 #

## Learning more about what we can do in react will help us develop our apps to be better. It will also allow us to add more functionality to our apps and hopefully increase user retention ##

### *What does .map() return?* ###

- It returns an array of similar size, changing the values depending on the parameters set

### *If I want to loop through an array and display each value in JSX, how do I do that in React?* ###

- You can use .map() to loop through an array and display each value

### *Each list item needs a unique ____* ###

- Each list item needs a unique key

### *What is the purpose of a key?* ###

- To give each object a unique identifier 

### *What is the spread operator?* ###

- The spread operator is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments

### *List 4 things that the spread operator can do* ###

- Add items to arrays
- combine arrays or objects
- spreading an array out into a functions arguements
- Converting NodeList to an array

### *Give an example of using the spread operator to combine two arrays* ###

- const myArray = [`Hi`,`You`,`!`]
const yourArray = [`I,`am`,`here`]
const ourArray = [...myArray,...yourArray]
console.log(...ourArray) // 'Hi' 'you' '!' 'I' 'am' 'here'

### *Give an example of using the spread operator to add a new item to an array* ###

- const fruits = ['🍏','🍊','🍌','🍉','🍍']
const moreFruits = [...fruits];
console.log(moreFruits) // Array(5) [ "🍏", "🍊", "🍌", "🍉", "🍍" ]
fruits[0] = '🍑'
console.log(...[...fruits,'...',...moreFruits]) //  🍑 🍊 🍌 🍉 🍍 ... 🍏 🍊 🍌 🍉 🍍

### *Give an example of using the spread operator to combine two objects into one* ###

- const objectOne = {lives: 3};
    const objectTwo = {lives: 2};
    const objectThree = {...objectOne,...objectTwo} //{lives: 3, lives: 2}

### *In the video, what is the first step that the developer does to pass functions between components?* ###

- First they need to write the function 

### *In your own words, what does the increment function do?* ###

- It takes in the person, and the increases the count depending on which name is passed through

### *How can you pass a method from a parent component into a child component?* ###

- You can use this."the name of the method you would like to pass"

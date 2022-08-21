# Reading 6 #

## Learning about different data types such as objects as compared to strings gives us more flexibility when writing JS. Object data types help us group together several variables and functions. DOM is important to learn about because it allows programs to change the document structure style and content ##

### *How would you describe an object to a non-technical friend you grew up with?* ###

- In JavaScript, an object is a standalone entity, with properties and type. Compare it with a cup, for example. A cup is an object, with properties. A cup has a color, a design, weight, a material it is made of, etc. The same way, JavaScript objects can have properties, which define their characteristics.

### *What are some advantages to creating object literals?* ###

- It is very common to create an object using an object literal when you want to transfer a series of structured, related data items in some manner, for example sending a request to the server to be put into a database. Sending a single object is much more efficient than sending several items individually, and it is easier to work with than an array, when you want to identify individual items by name

### *How do objects differ from arrays?* ###

- Sending a single object is much more efficient than sending several items individually, and it is easier to work with than an array, when you want to identify individual items by name

### *Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation* ###

- The object name (person) acts as the namespace — it must be entered first to access anything inside the object. Next you write a dot, then the item you want to access — this can be the name of a simple property, an item of an array property, or a call to one of the object's methods

### *Evaluate the code below. What does the term this refer to and what is the advantage to using this?* ###

- The first accesses the first data point within the object, in this case it would be the first name of the dog, spot. In the seconn instance it accesses the age of the dog which would be 2

### *What is the DOM?* ###

- The Document Object Model (DOM) is a programming interface for web documents. It represents the page so that programs can change the document structure, style, and content. The DOM represents the document as nodes and objects; that way, programming languages can interact with the page

### *Briefly describe the relationship between the DOM and JavaScript* ###

- The previous short example, like nearly all examples, is JavaScript. That is to say, it is written in JavaScript, but uses the DOM to access the document and its elements. The DOM is not a programming language, but without it, the JavaScript language wouldn't have any model or notion of web pages, HTML documents, SVG documents, and their component parts. The document as a whole, the head, tables within the document, table headers, text within the table cells, and all other elements in a document are parts of the document object model for that document. They can all be accessed and manipulated using the DOM and a scripting language like JavaScript
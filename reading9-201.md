# Reading 9 #

## This topic is important because its how a user interacts with a webpage. They can fill out data and allows our website to collect that data. Events are important because they signal to the user that something is interactive ##

### *Why are forms so important in web development?* ###

- Web forms are one of the main points of interaction between a user and a web site or application. Forms allow users to enter data, which is generally sent to a web server for processing and storage (see Sending form data later in the module), or used on the client-side to immediately update the interface in some way (for example, add another item to a list, or show or hide a UI feature).

### *When designing a form, what are some key things to keep in mind when it comes to user experience?* ###

- Before starting to code, it's always better to step back and take the time to think about your form. Designing a quick mockup will help you to define the right set of data you want to ask your user to enter. From a user experience (UX) point of view, it's important to remember that the bigger your form, the more you risk frustrating people and losing users. Keep it simple and stay focused: ask only for the data you absolutely need

### *List 5 form elements and explain their importance* ###

- elements: < form >, < label >, < input >, < textarea >, and < button >

- This element formally defines a form. It's a container element like a < section > or < footer > element, but specifically for containing forms; it also supports some specific attributes to configure the way the form behaves. All of its attributes are optional, but it's standard practice to always set at least the action and method attributes

- Our contact form is not complex: the data entry portion contains three text fields, each with a corresponding < label >:

- The input field for the name is a single-line text field

- The input field for the e-mail is an input of type email: a single-line text field that accepts only e-mail addresses.
The input field for the message is a < textarea >; a multiline text field

- The < button > element also accepts a type attribute — this accepts one of three values: submit, reset, or button.

- A click on a submit button (the default value) sends the form's data to the web page defined by the action attribute of the < form > element.

- A click on a reset button resets all the form widgets to their default value immediately. From a UX point of view, this is considered bad practice, so you should avoid using this type of button unless you really have a good reason to include one.

- A click on a button button does nothing! That sounds silly, but it's amazingly useful for building custom buttons — you can define their chosen functionality with JavaScript

### *How would you describe events to a non-technical friend?* ###

-Events are actions or occurrences that happen in the system you are programming, which the system tells you about so your code can react to them

### *When using the addEventListener() method, what 2 arguments will you need to provide?* ###

- that takes at least two arguments: the name of the event and a function to handle the event. So we call the button's addEventListener() method, passing in:

- the string 'click', to indicate that we want to listen to the click event

- a function to call when the event happens. In our case the function generates a random RGB color and sets the page < body > background-color equal to that color

### *Describe the event object. Why is the target within the event object useful?* ###

- Sometimes, inside an event handler function, you'll see a parameter specified with a name such as event, evt, or e. This is called the event object, and it is automatically passed to event handlers to provide extra features and information

### *What is the difference between event bubbling and event capturing?* ###

- Event bubbling and capture are terms that describe phases in how the browser handles events targeted at nested elements
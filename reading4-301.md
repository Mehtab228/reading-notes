# React and Forms #

## Adding forms in react could increase functionality by allowing th visiter to directly search for what they are looking for or even filter through your images only selecting what they are looking for. For example in horned beast they could select to only display animals with 2 horns. ##

### *What is a ‘Controlled Component’?* ###

- An input form element whose value is controlled by React in this way is called a “controlled component”

### *Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why* ###

- We should store the users responses from the form first before we update state. If state trys to  update with their response before its stores its going to break the site

### *How do we target what the user is entering if we have an event handler on an input field?* ###

- You would create an event.target.value like you would in vanilla javascript

### *Why would we use a ternary operator?* ###

- it makes the code dryer and simpler to read

### *Rewrite the following statement using a ternary statement:* ###

- x===y ? console.log(true) : console.log(false)

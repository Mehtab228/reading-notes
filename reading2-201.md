# Reading 2 #

## Understanding the differences between HTML, CSS, and JavaScript is important when designing our application. It is important to understand what each language is capable of and when we would use what feature ##

1. *Why is it important to use semantic elements in our HTML?*

-We need to make sure we are using the correct elements, giving our content the correct meaning, function, or appearance. In this context, the h1 element is also a semantic element, which gives the text it wraps around the role (or meaning) of "a top level heading on your page" It will automatically apply certain features such as making the h1 text appear larger

2.*How many levels of headings are there in HTML?*

-There are a total of 6 heading elements, each element represents a different level of content in the document; <h1> represents the main heading, <h2> represents subheadings, <h3> represents sub-subheadings, and so on

3.*What are some uses for the sup and sub elements?*

-You will occasionally need to use superscript and subscript when marking up items like dates, chemical formulae, and mathematical equations so they have the correct meaning. The <sup> and <sub> elements handle this job. 

4.*When using the <abbr> element, what attribute must be added to provide the full expansion of the term?*

-Let's look at an example:

<p>We use <abbr>HTML</abbr>, Hypertext Markup Language, to structure our web documents.</p>

<p>I think <abbr title="Reverend">Rev.</abbr> Green did it in the kitchen with the chainsaw.</p>

These will come out looking something like this:

We use HTML, Hypertext Markup Language, to structure our web documents.

I think Rev. Green did it in the kitchen with the chainsaw.

5.*What are ways we can apply CSS to our HTML?*

-with an external stylesheet, with an internal stylesheet, and with inline styles

6.*Why should we avoid using inline styles?*

-First, it is the least efficient implementation of CSS for maintenance. One styling change might require multiple edits within a single web page. Second, inline CSS also mixes (CSS) presentational code with HTML and content, making everything more difficult to read and understand. Separating code and content makes maintenance easier for all who work on the website

7.selector:h2

-CSS declaration: color and padding

-black, 5px

8.*
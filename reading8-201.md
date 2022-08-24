# Reading 8 #

## It is important to learn more about different tools at our disposal when creating the CSS for our page. Being able to fine tune everything can make a page more appealing and allow the user to more easily take in information ##

### *Flexbox is designed for one-dimensional content. Explain what this means* ###

- The Flexible Box Layout Model (flexbox) is a layout model designed for one-dimensional content. It excels at taking a bunch of items which have different sizes, and returning the best layout for those items

### *Explain the difference between the main axis and cross axis* ###

- The main axis is the one set by your flex-direction property. If that is row your main axis is along the row, if it is column your main axis is along the column

- The cross axis runs in the other direction to the main axis, so if flex-direction is row the cross axis runs along the column.

### *How can using certain properties of flexbox negatively impact accessibility?* ###

- You should be cautious when using any properties that reorder the visual display away from how things are ordered in the HTML document, as it can negatively impact accessibility. The row-reverse and column-reverse values are a good example of this. The reordering only happens for the visual order, not the logical order. This is important to understand as the logical order is the order that a screen reader will read out the content, and anyone navigating using the keyboard will follow

### *What are some advantages of using flexbox over float?* ###

- The following simple layout designs are either difficult or impossible to achieve with such tools in any kind of convenient, flexible way:

- Vertically centering a block of content inside its parent.

- Making all the children of a container take up an equal amount of the available width/height, regardless of how much width/height is available.

- Making all columns in a multiple-column layout adopt the same height even if they contain a different amount of content

### *How does this topic connect with your long term goals?* ###

- Using flexbox can help us allign multiple elments that are stored in the same container in a way that could improve readability. For example if you have 2 pictures and a title in your header, a flexbox could help you allign them so the title is between the pictures in a more efficient way
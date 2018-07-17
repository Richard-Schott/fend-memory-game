# Memory Game Project

## Table of Contents

* [Instructions](#instructions)
* [Contributing](#contributing)

## Instructions

The starter project has some HTML and CSS styling to display a static version of the Memory Game project. You'll need to convert this project from a static project to an interactive one. This will require modifying the HTML and CSS files, but primarily the JavaScript file.

To get started, open `js/app.js` and start building out the app's functionality

For specific, detailed instructions, look at the project instructions in the [Udacity Classroom](https://classroom.udacity.com/me).

## Contributing

This repository is the starter code for _all_ Udacity students. Therefore, we most likely will not accept pull requests.

For details, check out [CONTRIBUTING.md](CONTRIBUTING.md).



## Comments
1. My first event, a click function, needs to have a variable to define the cards. I approached this backwards, using the document to toggle .card.
2. Use an event parameter to target, otherwise he inner function targets all cards when the toggle is applied.
3. Matthew Cranford's guide, and Stack Overflow, say that I need to create a function that passes the click event handler to it.
	Specifically, I need to pass the click event to a function that toggles the card elements. In a prior exercise, I noticed the toggle
	automatically created a class or 'open'. Do I need an open and closed class toggle?
4. 
5. ".match" appears when two cards of the same type appear. A conditional is necessary to demonstrate equal pairs.
6. ".card" appears blank
7. ".open" and ".show" appear on an unmatched card.

## Acknowledgements
First, I'd like to thank Sachin, Judi Portwood, Lou, and drunkenkismet from the Grow With Google FEND Slack for their help.
Kj from the FEND Slack gave me the final bit of help that I needed to have my first usable function!

##References
1. Matthew Cranford, "Memory Game Walkthrough": https://matthewcranford.com/memory-game-walkthrough-part-1-setup/
2. Stack Overflow: "jQuery: How to get the event object in an event handler function without passing it as an argument?"
	https://stackoverflow.com/questions/5849370/jquery-how-to-get-the-event-object-in-an-event-handler-function-without-passing
3. "HTML DOM classList Property" on w3schools: https://www.w3schools.com/jsref/prop_element_classlist.asp
4. "Stack Overflow: JavaScript - pushing Elements with same Class into array & using each in a loop": https://stackoverflow.com/questions/8899661/javascript-pushing-elements-with-same-class-into-array-using-each-in-a-loop

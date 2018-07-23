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
1. Use an event parameter to target, otherwise he inner function targets all cards when the toggle is applied.
2. ".match" appears when two cards of the same type appear. A conditional is necessary to demonstrate equal pairs.
3. ".open" and ".show" appear on an unmatched card.

## Guiding ideas

1. i is back; li is front. Front has id, pass them into array. randomized array, pass elements to it. array held image list; img tag with src
2. Store flipped cards into an array, then push them into it. This should be a function.
3. clickEvent isn't global scope, though. How exactly am I identifying what I'm pushing? Events and variables are function scope.
4. call array into on click, put this into the other function. copy/paste into other one.
5. id i elements in an array (e.g. i fafa bicycle, then compare id getElementById)
6. convert to string, compare string data in a conditional for equality?
7. possible to set an id and retrieve it, perhaps in an object.
8. retrieve info from child node in the array, get text, call it, object gets id, compared it (innerHTML) and textContent

## Acknowledgements
First, I'd like to thank Akyya, Sachin, Judi Portwood, Lou, and drunkenkismet from the Grow With Google FEND Slack for their help.
Kj from the FEND Slack gave me the final bit of help that I needed to have my first usable function!

##References
1. Matthew Cranford, "Memory Game Walkthrough": https://matthewcranford.com/memory-game-walkthrough-part-1-setup/
2. Stack Overflow: "jQuery: How to get the event object in an event handler function without passing it as an argument?"
	https://stackoverflow.com/questions/5849370/jquery-how-to-get-the-event-object-in-an-event-handler-function-without-passing
3. "HTML DOM classList Property" on w3schools: https://www.w3schools.com/jsref/prop_element_classlist.asp
4. "Stack Overflow: JavaScript - pushing Elements with same Class into array & using each in a loop": https://stackoverflow.com/questions/8899661/javascript-pushing-elements-with-same-class-into-array-using-each-in-a-loop

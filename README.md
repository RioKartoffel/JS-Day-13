# JS-Day-13
Random Choice Picker

This code creates a simple HTML webpage with some CSS styling and JavaScript functionality.

The HTML code creates a basic structure of the page with a header, textarea and a div element with an id of "tags". The head section of the HTML file contains meta information, the title of the page, and a link to the stylesheet.

The CSS code styles the page's background color, font, and layout. It styles the textarea, the tag elements, and the highlight class for when a tag is selected.

The JavaScript code provides the main functionality of the page. The code sets up a listener for the keyup event on the textarea and calls the "createTags" function whenever a comma is entered. The "createTags" function takes the input from the textarea, splits it into an array of strings (representing the tags), filters any empty strings, trims any whitespaces, and adds each tag to the page as a span element.

The keyup event listener also calls the "randomSelect" function if the key entered is the enter key. The "randomSelect" function runs an interval that repeatedly calls the "pickRandomTag" function and the "highlightTag" function in quick succession to give the appearance of randomly highlighting a tag. After 30 intervals, the interval is cleared, and the last selected tag remains highlighted.

So in summary, this code creates a simple random tag picker that allows the user to input a list of tags separated by commas and then randomly selects one of them after the user presses the enter key.

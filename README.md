# DOM-Tasks

First Tasks in Javascript
Exercise #1 (1): Changing text
Extend this HTML page such that on moving the mouse over the yellow box the text changes to "Can I help you?". Then, when the mouse is moved outside the box the text changes back to "Hello world!".
Exercise1

Exercise #2 (2): Changing colors
This page contains a 200x200px div. Write JS code that sets the initial color of the div to blue, then changes the color when the div is clicked. On the first click, it changes from blue to red, on the next click from red to green, then from green to blue (and once it's blue, it starts all over again).
In this exercise, you are only allowed to make changes inside <script>...</script> and cannot change other parts of the HTML code.
Exercise2

Exercise #2b (3): Randomizing initial color
Extend the previous exercise such that the div's initial color is chosen randomly.
Can you extend the code to work with an array of arbitrary colors? Whenever the div is clicked, change the color to the next on in the array (and start over after the last color).
Exercise #3 (4): Changing images
The page shows a select list and a "no image" picture by default.
Once the user changes the selection in the list, display the selected image.
Set the src of the image to the option value and the alt of the image to the name of the option.
Exercise3 Exercise3/2

Exercise #4 (5): Formatting text
Create a simple what-you-see-what-you-get text editor.
Change the text inside the "text" div according to the form selections.
You can find the starter HTML file with the form controls here.
Exercise4

Exercise #5 (6): Input check
You are given a form with two password fields and a submit button.
Perform input check and display an error message next the the corresponding field if there is an error.
Passwords must be at least 6 characters long.
The two passwords must match.
The placeholders for the error messages have already been prepared (div-s with class "err").
By default the submit button should be hidden. Display the button only when there are no errors.
Exercise5/1 Exercise5/2 Exercise5/3

Exercise #6 (7): Content show/hide
You are given the starter HTML file.
By default, show only the article headings (this can be achieved by setting the display property of the div with the text to "none" using inline CSS).
Clicking the "show" link should make the article body appear and the "show" link to disappear.
Clicking the "hide" link should make the article body disappear and the "show" link appear.
Exercise6

Exercise #7 (8: Simple playlist
Create a simple playlist application where users can add songs to a list. The song here is just a non-empty string.
The starter HTML file contains the form and an empty playlist. There is an external CSS file with the style declarations.
Exercise7

Exercise #7b (9): Advanced playlist
Extend the previous exercise such that songs can be removed too. Add a delete link or icon to each song; clicking the link/icon should remove the song from the list.
Exercise #8 (10): Color picker
Make a color picker that displays a color palette; display colored tiles (rectangles) in the "colors" div.
When a colored tile is clicked:
write the code of that color inside the "selected" div;
set the background of the "selected" div to that color.
You are given the HTML file and part of the JS code that collects the different colors in an array. (Only the JS file needs to be edited.)
Exercise8

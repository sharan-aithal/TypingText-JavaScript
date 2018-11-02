# TypingText-JavaScript

Here we use a JavaScript to moving text like we typing a text.

 * An object-oriented Typing Text script, to allow for multiple instances.
 * A script that causes any text inside any text element to be "typed out", one letter at a time.
 * Note that any HTML tags will not be included in the typed output, to prevent them from causing problems. 
 * Tested in Firefox v1.5.0.1, Opera v8.52, Konqueror v3.5.1, and IE v6.
 * Browsers that do not support this script will simply see the text fully displayed from the start, including any HTML tags. 
 * Functions defined: ```TypingText(element, [interval = 100,] [cursor = "",] [finishedCallback = function(){return}])``` : Create a new TypingText object around the given element.
 * Optionally specify a delay between characters of interval milliseconds. cursor allows users to specify some HTML to be appended to the end of the string whilst typing.
 * Optionally, can also be a function which accepts the current text as an argument.
 * This allows the user to create a "dynamic cursor" which changes depending on the latest character or the current length of the string. finishedCallback allows advanced scripters to supply a function to be executed on finishing.
 * The function must accept no arguments. `TypingText.run()` : Run the effect. static `TypingText.runAll()` : Run all TypingText-enabled objects on the page.

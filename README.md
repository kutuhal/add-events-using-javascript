# add-events-using-javascript
#### What it does?
HTML code is minimal here. A simple input field is there. Everytime a key is pressed it gives an alert. Also, it gives the number of times the key was pressed.
####Why?
This was done to crystalize the learning of adding events using JavaScript (i.e. **DOM Level Event Handlers** ) instead of **_HTML Event Handlers_**.

#### Points to remember
- We have to ensure that _addEventListener_ related commands are excuted after loading of HTML. Else we will get an error because an event cannot be added to the element which is not loaded.
- To take care of above point, you will notice that the JavaScript is placed at the end of HTML body tag. 
- Other option could have been to put that block of code in function and call the function after the HTML is loaded.

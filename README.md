# Todo App using Javascript

## Problem Statement
Create a simple todo list  site in Javascript.

## Requirements
- Display a navigation bar with todo application name and username. No authentication and user management required. Just display some username.
- Display  default todo list items loaded from a json file asynchronously. 
This json file should have multiple todo list objects. Each object should have title, todo item, author and date properties.
- Create new todo item using an input area. This need not be persisted on the server/database.
 
## Implementation
- The todo.js file asynchronously reads the JSON data stored in an external file 'data/todo.json'.
- JSON object is parsed and rendered on the browser based on whether the task is completed or pending.
- The user inputs Title, Author and Todo items to create a new task.
- The detailed Date timestamp when the task was created is also displayed for each todo item.
- The user can mark the pending 'todo' task as complete and move it to the 'completed' list. 
Similarly, a 'completed' task can be unmarked as complete and moved back to the pending or 'todo' list.
- Any todo task can be deleted from the either of the task list.
- On clicking the area where tasks appear on the browser, the task list can be updated.
    
## Working:

- Open the todo.html file on browser like Mozilla Firefox (preferred) or Google Chrome.
- You can then see the Todo App with some pre-loaded todo items loaded on the browser.
- The user can now add, update or delete any of the todo tasks.


## References:

https://codepen.io/franklynroth/pen/ZYeaBd
https://github.com/themaxsandelin/todo/tree/master/resources
http://archive.oreilly.com/oreillyschool/courses/javascript2/TodoListApp.html
https://codepen.io/jaballadares/pen/Hwebq
https://www.w3schools.com/howto/tryit.asp?filename=tryhow_js_todo
https://codepen.io/KryptoniteDove/post/load-json-file-locally-using-pure-javascript
https://github.com/amuthanarulraj/stickies


## Author
- Vrushali Shah

## TO DO LIST

![]()

## ABOUT

> *The most comprehensive of all the Odin Projects so far, the objective was to incorporate all the skills and knowledge I have practiced along the way to create a fully functioning web app in the form of a to-do application:*

- Usage of classes, and factory functions. Logic primairly used here involves getters and setters as foundations.
- DOM Manipulation, with more focus on parentNode/childNode relationship.
- For loops, arrays and object notation crucial to form functional logic.
- Toggling inputs via adding/removing classes with on click event listeners.
- Using .filter, .some, .map methods on arrays of items.
- Dates formatted and aligned with today/this week project tabs via the package 'date-fns' and its preset modules.
- Local storage incorporated, saving the data in a JSON file with a specific key, as well as functions to remove data & update data as user inputs new projects and tasks.

## STRUCTURE
> *Each part of the logic was divided into separate modules then bundled together with webpack. Containing each page of logic into separate modules allows for cleaner, portable and unique code.*

The logic is separated by:

- Factory functions for object 'Project'
- The same as above for object 'Task' => each project contains its own array of tasks
- Class module of 'ToDoList' which contains its own array of projects, as well as 'default' projects of 'All', 'Today', 'This Week'
- A module for local storage.
- A module specified for user interface => such as creating & displaying tasks/projects, showing & hiding of pop-up forms and editing elements' contents. 

## THIS PROJECT WAS MADE WITH

- ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)   
- ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)   
- ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
- ![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)

## USEFUL RESOURCES

- Stack Overflow
- Geeks for Geeks
- W3C Schools
- Font Awesome Icons
- Mozilla Developer Network
- Javascript Documentation
- ![date-fns](https://date-fns.org/)

## LINKS

[Try the assignment on The Odin Project](https://www.theodinproject.com/lessons/node-path-javascript-todo-list)

[Organise your busy schedule here!](https://gangoffour199.github.io/restaurant/)

This markdown file was created using [dilinger.io](https://dillinger.io/)

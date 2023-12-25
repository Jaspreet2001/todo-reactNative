https://github.com/Jaspreet2001/todo-reactNative/assets/78601370/7c982392-89bc-404e-8ed7-bd0dfdb8c468

![re2](https://github.com/Jaspreet2001/todo-reactNative/assets/78601370/c939d16f-ab53-47b2-8cfc-59b20cb4978a)
![re1](https://github.com/Jaspreet2001/todo-reactNative/assets/78601370/96ca5c63-127e-4474-add2-2360e53a7202)
![to2](https://github.com/Jaspreet2001/todo-reactNative/assets/78601370/a1eb907b-bcbd-4615-8b57-a97f92119ae8)
![to1](https://github.com/Jaspreet2001/todo-reactNative/assets/78601370/e85c4a6d-797e-40b1-b0ba-8112aa0f167c)
---------------------------------------------------------------------------------------------------------------------------------------------------------------------
Certainly! The provided code is a simple todo app built using React Native. Here's a breakdown of how it works:

Features:------------------------------------------------------------------------------------------------------------

Adding Todo:
Users can input a task into the text input field.
Pressing the "Add Todo" button adds the entered task to the list.

Deleting Todo:
Each todo item displayed in the list is clickable.
Clicking on a todo item deletes it from the list.

Code Explanation:----------------------------------------------------------------------------------------------------
State Management:
useState hook is used to manage state variables: todoItems to store the list of todos, and text to store the text input value.

Add Todo:
addTodo function checks if the text input is not empty, then adds a new todo item to the todoItems list.
It assigns a unique key to each todo item using Date.now().

Delete Todo:
deleteTodo function filters the todoItems list based on the key of the clicked todo item and updates the state to reflect the new list without the deleted todo.

Rendering Todo List:
The FlatList component renders the list of todos.
Each todo item is displayed as a TouchableOpacity component, allowing deletion when clicked.

Styling:-------------------------------------------------------------------------------------------------------------
Styles for various components are defined using the StyleSheet.create method, providing a basic user interface for input, buttons, and the todo list.

Usage:--------------------------------------------------------------------------------------------------------------

Input Todo:
Users enter a task in the text input field provided.
Press the "Add Todo" button to add the task to the list.

Delete Todo:
Click on any task displayed in the list to remove it from the todo list.

Running the App:-------------------------------------------------------------------------------------------------

Setup:
Ensure React Native is installed and the project directory is created.

Run the App:
Using the React Native CLI commands (react-native run-android or react-native run-ios), the app can be launched on an Android or iOS emulator or a connected device.

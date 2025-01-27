# React Todo App with API

## Description

This is a Todo application integrated with an API that allows you to create, delete, toggle the status, and rename tasks. The app supports the following features:

- Adding tasks
- Deleting tasks
- Toggling task status (marking as completed/incomplete)
- Renaming tasks
- Supporting asynchronous requests and loading states

## Main Features

### Toggling Task Status
- You can mark a task as completed or incomplete.
- A loading indicator is displayed when the status is being updated.
- If there is an error updating the task, a notification saying "Unable to update a todo" is shown.

### Renaming a Task
- To edit a task's title, double-click on the task.
- Save changes by pressing "Enter" or when the input field loses focus.
- If the new title is the same as the old one, editing is canceled.
- If the new title is empty, the task will be deleted.
- While waiting for the API response, a loading indicator is shown.

### Toggling All Tasks Status
- There is a button to mark all tasks as completed or incomplete at once.
- The button's state changes depending on whether all tasks are completed.

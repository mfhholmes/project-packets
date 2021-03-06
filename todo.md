# to-do list

In this project, you will create a todo list application that can be added to your Chrome browser.

This project has a core set of functionality that will need to be completed in stages, but at each stage there are optional extra features that can be added if you are confident and have the time.

## feature list

1. Create a to-do item
  1.1 add a priority field
  1.2 add a due date field
2. Store the to-do list in local storage
  2.2 create a download link to download the list to your local drive
3. Load the todo list from local storage
  3.2 flag a reminder if the due date is close (if you've done 1.2)
4. Sort the items by name
  4.1 sort the items by priority if you did 1.1
  4.2 sort the items by due date if you did 1.2
5. Display a 'completed' button and mark the to-do item as complete if ticked
  5.1 add sub-tasks that all need to be completed for the main task to be complete
6. Purge the list of completed items
  6.1 remember how many tasks were completed and display a history of task completion

## files

*manifest.json*

~~~ javascript
{
  "name": "To Do List",
  "description": "This app keeps your to do list tidy",
  "version": "1.0",
  "manifest_version": 1,
  "app": {
    "launch": {
      "local_path": "todo.html"
    }
  }
}
~~~

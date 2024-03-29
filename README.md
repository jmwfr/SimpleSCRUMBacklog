# SIMPLE SCRUM BACKLOG

## Introduction

This a simple PHP/Javascript SCRUM backlogs manager.

I was in a training and the guy was explaining us how to manage a dev team SCRUM backlog and I have been surprised of the amount of post-it we have spent to do that!!!

This is just a personal project, there is no security or concurent users management.

## Prerequisites

A simple webserver with PHP enabled and an internet connection is enough to make it work

## Usage
To add a task to the backlog just click the "Add Task" button, it will be directly added to the 'Todo' column.

You can edit the content of a task by just double-cicking it.
While editing you can set the task priority level.

To move a task between development steps, just drag and drop it on the corresponding column.
You can also sort (order ascending or descending) tasks by priority level using the arrows in the columns headers.

Once you have saved a backlog, you can select it from the "Select a backlog list" to load it again.

You can rename a backlog by changing its name in the "Backlog Name" field and clicking on "Rename Backlog" button.

To delete a backlog just select it in the list and click the "Delete Selected" button.

You can use the "Reset" button to empty all the backlog workspace (you'll be asked to save your work before that if the current loaded backlog has been modified and not saved).

## Authors

[Jean-Marc Aubertin](https://github.com/jmwfr)

## License

This software is licensed under the MIT license (details [here](LICENSE.md))

## Todos and Improvements

* [x] Update the select list when a backlog is saved
* [x] Add a remove backlog option
* [x] Add a rename backlog option
* [x] Move js and css files to distinct folders
* [x] Check if backlog was saved before reseting
* [x] Add sorting by priority

If you have any other ideas feel free to ask!   
# Task-and-Notes-Manager

Project: Task and Notes Manager

Objectives
•	The website is a task manager
•	Each task has following properties
o	Title
o	Description
o	Due Date
o	Status: incomplete / completed
o	Priority: High / Medium / Low
•	Each task can have notes added to it as well
o	One task can have multiple notes under it

User Interface 
•	The main page should show a list of tasks and a form to add new tasks
•	Clicking on any task should expand and show the notes under it and show an input box to add more notes to it
•	We should be able to sort the list of tasks by 
o	Due date (ascending and descending)
o	Priority (high to low)
o	Status (incomplete at top, completed at bottom)
•	When adding a task following fields to be filled
o	Title (compulsory)
o	Description (optional)
o	Due Date (compulsory), by default input box should have tomorrow’s date
o	Priority (by default medium selected)
o	All new tasks are to be added in ‘incomplete’ state
•	Once added, we should be able to change 
o	Due date
o	Priority
o	Completed/Incomplete state (using a checkbox)

Technical Implementation 
•	Backend should be in NodeJS
•	Task and notes data should be saved in a database (you can use SQLITE with Sequelize) 
•	Frontend will communicate with backend via JSON API 
•	Frontend will be in HTML/CSS/JS
•	Using common CSS framework like Bootstrap is allowed on frontend
•	Using common CSS library like jQuery allowed on frontend

API Guide 
Some hints as to how the API should behave 
•	GET        /todos – list all todos in array
•	POST     /todos – add a new todo
•	GET        /todos/4 – details of todo with id = 4 
•	PATCH /todos/4 – update details of todo with id = 4 
•	GET        /todos/4/notes – get list of all notes under todo with id = 4 
•	POST     /todos/4/notes – add a new note under todo with id = 4

Submission 
•	Create a git repo to start work on this project
•	Make well-described git commits. Marks will be deducted for git commit messages that make no sense 
•	Host the site via Heroku 
•	You can commit a sample todos.db file in the code, so when project is deployed, it already has some data
•	Submit project via this form https://cb.lk/2GR-s 
•	Submission deadline is Wed 15th Apr – 11:59PM
















Git Command to upload Any Folder(Step By Step)




Create a new repository on GitHub.
Open Git Bash.
Change the current working directory to your local project.
Initialize the local directory as a Git repository.

$ git init
Add the files in your new local repository. This stages them for the first commit.

$ git add .
Commit the files that you've staged in your local repository.

$ git commit -m "First commit"
At the top of your GitHub repository's Quick Setup page, click to copy the remote repository URL.

In the Command prompt, add the URL for the remote repository where your local repository will be pushed.

$ git remote add origin <remote repository URL>
# Sets the new remote
$ git remote -v
# Verifies the new remote URL
Push the changes in your local repository to GitHub.

$ git push origin master

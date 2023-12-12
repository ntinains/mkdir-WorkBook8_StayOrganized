# Stay Organized - Workbook 8's Workshop

## Project Description

Stay Organized is a web application that allows users to keep track of a list of things they need to accomplish. This project interfaces with a REST API for back-end data storage and manipulation.

### Example Task
- Category: "Personal Task"
- Description: "Finish studying for ENG 211 exam"
- Deadline: "2022-12-15"
- Priority: "Medium"

## Features

- **View ToDo List**: Users can view the ToDo tasks of a specific registered user.
- **Add ToDo Task**: Users can add new ToDo tasks assigned to them.
- **Dynamic Pages**: The site will feature an index page, a user-specific ToDo view page, and a task addition page.

## Pages

- `index.html`: A home page that highlights the "Stay Organized" website.
![Homepage](/frontend/Images/homepage.PNG)

- `todos.html`: A page for viewing all ToDo tasks for a specific user by selecting from a dropdown menu.

![ToDos](/frontend/Images/getToDoTask.PNG)

- `newUser.html`: A page to create a new user.

![NewUser](/frontend/newUser.html)

- `newTodos.html`: A page to add new ToDo tasks.

![newTodos](/frontend/newToDo.html)


## Setup

### Cloning the Repository

Clone the REST API repository needed for the back-end services:

```bash
git clone https://github.com/DevelopIntelligenceBoulder/stay-organized-workshop-express-server

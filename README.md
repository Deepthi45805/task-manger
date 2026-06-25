Task Manager Web App

Overview

Task Manager is a full-stack web application that helps users create, view, and delete tasks. The application uses Node.js, Express.js, and MongoDB for backend functionality, while HTML, CSS, and JavaScript provide a responsive user interface.

Features

- Add new tasks
- View all tasks
- Delete tasks
- MongoDB database integration
- RESTful API implementation
- Responsive user interface

Tech Stack

- Frontend: HTML, CSS, JavaScript
- Backend: Node.js, Express.js
- Database: MongoDB
- Version Control: Git & GitHub

Project Structure

task-manager/

- public/
  - index.html
  - style.css
  - script.js
- models/
  - Task.js
- server.js
- package.json
- .env

Installation

1. Clone the repository
2. Install dependencies

npm install

3. Create a .env file and add:

MONGO_URI=your_mongodb_connection_string

4. Start the server

npm start

5. Open in browser:

http://localhost:5000

Future Enhancements

- User Authentication
- Task Editing
- Task Categories
- Due Dates and Reminders
- Task Completion Status

Author

Deepthi

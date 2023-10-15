# Ve3-Task-Manager

# Backend API
 POST     /api/auth/signup  
 POST     /api/auth/login
 GET      /api/tasks
 GET      /api/tasks/:taskId
 POST     /api/tasks
 PUT      /api/tasks/:taskId
 DELETE   /api/tasks/:taskId
 GET      /api/profile

 # Frontend 
 /                 Home Screen (Public home page for guests and private dashboard (tasks) for logged-in users)
 /signup           Signup user page
 /login            User Login page
 /tasks/add        Add a new task
 /tasks/:taskId    Edit a task

 # npm command
 At root folder:

npm run dev: Starts both backend and frontend
npm run dev-server: Starts only backend
npm run dev-client: Starts only frontend

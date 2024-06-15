# To Do List Application 

![Screenshot 2024-06-06 155219](https://github.com/Chamindu77/Task-To_Do_List_Application/assets/117502200/3a6f97ac-c16f-46f7-ab64-b16eb523a057&width=1000&height=500)


This Todo app is a comprehensive task management application designed to help users manage their tasks efficiently. It features a user-friendly interface for adding, updating, and deleting titles and tasks. The application is fully responsive and includes robust backend support with user authentication, search, and sorting functionalities.

## Features

### Frontend
- **Technologies Used**: HTML, CSS, JavaScript
- **Functionalities**:
  - **Add a New Title**: Create a new category or title for tasks.
  - **Update the Title**: Edit existing titles to keep them up to date.
  - **Delete the Title**: Remove titles that are no longer needed.
  - **Add New Tasks**: Within each title, add tasks that need to be accomplished.
  - **Edit Tasks**: Update tasks to reflect changes.
  - **Delete Tasks**: Remove tasks that are completed or no longer relevant.
  - ![Screenshot 2024-06-06 161018](https://github.com/Chamindu77/Task-To_Do_List_Application/assets/117502200/b9d9d45f-28d9-49b0-85c9-849a0665e772)

- **Communication**: Uses Axios for frontend-backend communication.

### Backend
- **Technologies Used**: Node.js, Express
- **Database**: MongoDB
    - ![Screenshot 2024-06-06 162825](https://github.com/Chamindu77/Task-To_Do_List_Application/assets/117502200/b1a6fa0b-f7ad-4556-a3c0-3211783fe0fe)
    - ![Screenshot 2024-06-06 162917](https://github.com/Chamindu77/Task-To_Do_List_Application/assets/117502200/05640df7-aeae-40a0-933c-fcf3ab7c7039)


- **Functionalities**:
  - **CRUD Operations**: Handles Create, Read, Update, and Delete operations using REST API.
  - **Error Handling**: Properly manages errors to ensure a smooth user experience.

### Bonus Features
- **User Authentication**:
  - **Signup**: Allows new users to create an account.
   ![Screenshot 2024-06-06 162456](https://github.com/Chamindu77/Task-To_Do_List_Application/assets/117502200/65b28e28-185f-4a60-9b23-098dfa333428)

  - **Sign In**: Enables existing users to log in.
   ![Screenshot 2024-06-06 162547](https://github.com/Chamindu77/Task-To_Do_List_Application/assets/117502200/08b487a9-1158-4b92-a9c0-75613c74d8e2)


- **Search Functionality**: Users can search for specific tasks or titles. Then the relevent title will be searched as bellow.
  ![Search](https://github.com/Chamindu77/Task-To_Do_List_Application/assets/117502200/467b2e07-5e5b-496c-ab40-8e55fe027f32)


- **Sorting Functionality**: Tasks and titles can be sorted based on creation and updation.
- Sorting based on creation
     ![By Creations](https://github.com/Chamindu77/Task-To_Do_List_Application/assets/117502200/101dee93-3830-4481-8c0b-5a9554899f9f)


- Sorting based on updation
     ![By Updations](https://github.com/Chamindu77/Task-To_Do_List_Application/assets/117502200/869c75d2-e232-4875-9eab-1a14f5d32811)


## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/todo-app.git
   cd todo-app

2. **Frontend**
   
   2.1 Setup Frontend
     ```bash
    cd frontend
    npm i
     ```
     
  2.2 Run Frontend 
  
  ```bash
  npm start
  ```
   
3. **Backend**
   
   3.1 Setup Frontend

```bash
cd backend
npm i
```
  3.2 Run Frontend 
   
  ```bash
  npm start
  ```

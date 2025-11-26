



# Anti-Cheat Exam App Backend  🌟


An App that aims to stop cheating in online exams with the power of AI and ML, 
  
<p align="center">  
<img src="https://user-images.githubusercontent.com/28570857/178106216-25d91b1c-06cf-42fa-85fc-cf3540868b1f.png"/>  
</p>

  
  
## Features and Interfaces  
  
1. Login Page  
   - Login with the provided user id and password  
   
2. Home page  
   - Shows all the exams assigned to the user
   - The user can start an exam only on the correct timeslot
   - Logout through button in the app bar
     
3. Exam Page  
   - The user can answer MCQ-based questions
   - The user can also view their progress
   
   - ![image](https://user-images.githubusercontent.com/28570857/178106246-58941069-043d-448a-91c1-137f9b074931.png)  
    

7. AI-powered face motion detector  
   - We've used Google's on-device `ml-kit` to track the motion of the user's face.  
   - We can check if a user is trying to cheat by monitoring the position of their face
   
  
## Tech stack  
  
#### Frontend
   - Flutter
  

#### Backend
- Nodejs
- Express
- MongoDB

#### Other Tools
- Google's on-device ML Kit

## Points to remember while testing the app  
  
1. This is the backend part of the project, to test the actual app, read instructions on frontend [repository](https://github.com/prathamesh-mutkure/anti-cheat-exam-app)
  
## Instructions  
  
  
1. Clone the project locally
   - `git clone https://github.com/prathamesh-mutkure/anti-cheat-app-backend.git`  
3. Install node modules  
   - `npm install`  
5. Create a `.env` file and set the following variables
   -  `DB_URL`   
   - `PORT` (optional)
6. Run the app
   - `npm start`
   - `nodemon app.js` to test changes  
7. The backend should now run on `localhost` with default `8000` or  specified port
  
  


  

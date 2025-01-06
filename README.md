**Quiz App** is a web application that allows users to create, share, and take quizzes. It provides two types of quizes: Q&A type and poll type. This project is built using ReactJS for the frontend and Node.js, Express, and MongoDB for the backend.

## Features

### 1. Signup and Login
Users can sign up and log in to the application to create and manage their quizzes. Authentication ensures secure access to user data.JSON web token is used for secure authentication.

### 2. Quiz Creation
Create quizzes with up to 5 questions. You can choose between Q&A type and poll type quizzes. For each question, you can provide:
- **Text**
- **Image**
- **Text and Image**

**Q&A Type:** Includes a timer option for each question, and users can select the correct answer.

**Poll Type:** No timer is available, and users cannot select a correct answer.

### 3. Question-wise Analysis
After the quiz is taken, users can view a detailed analysis of each question. This feature helps in understanding how participants responded to each question.

### 4. Quiz Editing Feature
Users can edit their quizzes before sharing them. This feature allows you to update questions, options, and timer.

### 5. Dashboard
The dashboard provides an overview of all quizzes created by the user. It includes insights such as:
- Total number of quizzes created
- Total number of questions created
- Overall impressions on the quiz.

### 6. Take Test
Participants can take quizzes shared by other users. Depending on the quiz type, participants will answer questions with or without a timer.

## Technology Stack

### Frontend
- **ReactJS**
- **HTML**
- **CSS**
- **JavaScript**

### Backend
- **Node.js**
- **Express**
- **MongoDB**

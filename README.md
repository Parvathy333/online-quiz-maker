# Online Quiz Maker

## Project Overview
A full-stack web application that allows users to create, take, and manage quizzes. This platform provides a seamless experience for both quiz creators and participants.

## Features
* **User Authentication:** Secure user registration and login functionality.
* **Quiz Creation:** Users can create new quizzes by adding multiple questions and defining correct answers.
* **Quiz Listing:** View a list of all available quizzes.
* **Take Quiz:** Users can take quizzes and submit their answers.
* **Results Display:** See immediate results after completing a quiz.
* **User Dashboard:** A personalized welcome page after login.

## Technologies Used
* **Backend:**
    * Node.js
    * Express.js (for API)
    * MongoDB (Database)
    * Mongoose (ODM for MongoDB)
    * `jsonwebtoken` (for authentication)
    * `bcryptjs` (for password hashing)
    * `dotenv` (for environment variables)
    * `cors` (for cross-origin requests)
* **Frontend:**
    * HTML5
    * CSS3 (via `public/css/style.css`)
    * JavaScript (Client-side logic in `public/js/app.js`, `quiz-creation.js`, etc.)

## Setup and Installation (Local Development)

Follow these steps to get the project up and running on your local machine.

### 1. Prerequisites
* Node.js (LTS version recommended)
* MongoDB Atlas Account (for a cloud database)

### 2. Clone the Repository
```bash
git clone [https://github.com/Parvathy333/online-quiz-maker.git](https://github.com/Parvathy333/online-quiz-maker.git)
cd online-quiz-maker
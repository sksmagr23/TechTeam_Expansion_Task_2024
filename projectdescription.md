# Project Description

This project is a web application developed for handling form submissions from participants with E-cell design based UI. It provides a user-friendly web interface for participants to submit their details including their name, branch of study, email, phone number along with an optional image upload. The submitted data is then stored in a Firebase Firestore database organized into collections, and images are uploaded to Firebase Storage.

## Techs Used

- *React(Vite)* : The frontend(client-side) of the application is built using React, a popular JavaScript library for building user interfaces. Vite provides a fast and optimized development server

- *react-hook-form* : Used for form handling and validation in React.

- *Firebase* : A platform used to mobile and web applications. Firebase services used in this project include Firestore for the database and Storage for file uploads.

- *ES6 JavaScript* : Using modern JavaScript syntax and features for cleaner maintainable code

- *Tailwind CSS* : A utility-first CSS framework used for styling the UI components.

- *Git* : Version control system used for managing the source code.

## Firebase Implementation

- I have used Firebase Firestore database and Firebase Storage ,configured with Firebase SDK. I have used my own Firebase configuration by creating a project named "E-cell Form Task" in firebase console. 
- You can check the implementation in your firebase project by changing the config file in [firebase.js](./form-project/src/firebase.js)

- You can watch the working of the firebase setup in storing the form data at Database and storage
  [Click Here](./form-project/public/recording.mp4)
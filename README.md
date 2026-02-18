## 🎯 Aim

To implement global state management in a Single Page Application (SPA) using the React Context API and demonstrate state sharing across multiple components without prop drilling.

## 🛠️ Software Requirements

Node.js

React (Create React App)

VS Code or any code editor

Web Browser (Chrome recommended)

## 📖 Theory

In React applications, passing data from parent to deeply nested child components using props can become complex. This problem is known as prop drilling.

The React Context API provides a way to share global data (such as user information, themes, and settings) across components without manually passing props at every level.

Key Concepts Used:

createContext() – Creates a Context object

Provider – Supplies global state to components

useContext() – Consumes global state in child components

## 🏗️ Project Structure
src/
│
├── context/
│     └── GlobalContext.js
│
├── components/
│     ├── Navbar.jsx
│     └── Profile.jsx
│
├── App.js
├── App.css
└── index.js

## ⚙️ Features Implemented

✔ Global state management using Context API
✔ Theme switching (Light/Dark mode)
✔ User name update reflected across components
✔ Avoids prop drilling
✔ Responsive and interactive UI
✔ Smooth transitions and animations

## 📘 Redux Counter Application

## 📝 Description

This project demonstrates centralized state management in a React application using Redux Toolkit.
A simple counter application is implemented where users can increment, decrement, and reset the counter value.

The application uses:

A single global store

Redux Toolkit for simplified configuration

useSelector to access state

useDispatch to update state

This experiment showcases how Redux manages predictable state updates through actions and reducers while maintaining a scalable folder structure.

## 📁 Folder Structure

redux-counter-app/
│
├── src/
│   ├── app/
│   │    └── store.js
│   │
│   ├── features/
│   │    └── counter/
│   │         ├── counterSlice.js
│   │         └── Counter.js
│   │
│   ├── App.js
│   ├── App.css
│   └── index.js
│
└── package.json

## Screenshots Part1
## Dark
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a9cde06e-dbc7-433a-af0a-5789d709bfd7" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/fe4b1fd7-fd19-4abc-9dbe-62a18d3e0a09" />
## Light
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/30ed42d9-1950-4b53-b031-99b92e0911a1" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/29033dd7-c4b3-4397-913c-bd8d68690c17" />

## Screenshots Part2
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/456dad11-c9f7-4f78-8271-2d2fb6ae23be" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6da3b6ce-536a-4a32-b64f-6fc3f634f1b1" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/30dfde8a-4010-4ada-b6ac-f148606e2fc3" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/74f337bd-b8bf-430e-8d16-47945178194c" />


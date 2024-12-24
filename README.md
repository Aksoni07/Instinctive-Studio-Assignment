# Students CRUD Application

A simple and efficient **Students Management System** built using **React** and **Redux**, allowing users to perform CRUD (Create, Read, Update, Delete) operations on student data. This project demonstrates the power of Redux for state management in a React application.

## Features
- **Add Students**: Add new student records with relevant details.
- **View Students**: View a list of all registered students.
- **Edit Students**: Update existing student information.
- **Delete Students**: Remove student records from the list.

## Tech Stack
- **Frontend**: React, Redux, HTML, CSS
- **State Management**: Redux
- **Styling**: CSS/SASS (if used)
- **Package Manager**: npm

## Installation

Follow the steps below to set up and run the project locally:

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd students-crud-redux
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Start the development server**:
   ```bash
   npm start
   ```

4. **View the application**:
   Open your browser and go to `http://localhost:3000`.

## Usage

1. Navigate to the application homepage to see the list of students.
2. Use the "Add Student" button to add new records.
3. Click the "Edit" button next to any student to modify their details.
4. Click the "Delete" button to remove a student from the list.

## Folder Structure

```plaintext
students-crud-redux
├── src
│   ├── components    # React components for the app
│   ├── redux         # Redux store, actions, and reducers
│   ├── styles        # CSS/SASS files
│   ├── App.js        # Main application component
│   └── index.js      # Entry point for React
├── public            # Public files
├── package.json      # Project metadata and dependencies
└── README.md         # Project documentation
```

## Scripts

- **Start Development Server**:
  ```bash
  npm start
  ```
- **Build for Production**:
  ```bash
  npm run build
  ```


# task-app

## Description
This repository contains a React application for managing tasks. The application utilizes custom HTTP hooks to interact with a Firebase Realtime Database. Users can add new tasks, view existing tasks, and handle errors gracefully.

## Usage
To use this repository, follow these steps:

1. Clone the repository to your local machine.
2. Install the necessary dependencies.
3. Configure Firebase Realtime Database URL in `App.js` and `NewTask.js` to point to your Firebase project.
4. Run the application.

## Components

### `App.js`
- Fetches tasks from Firebase Realtime Database.
- Allows users to add new tasks.
- Displays the list of tasks.

### `NewTask.js`
- Provides a form for users to enter and submit new tasks.
- Interacts with Firebase to add tasks.
- Handles errors gracefully.

### `TaskForm.js`
- Represents the task input form.
- Captures user input and triggers the submission of new tasks.

### `use-http.js`
- Custom hook for abstracting HTTP requests and error handling.
- Can be reused for making HTTP requests with different configurations.

## Contributions
Contributions are welcome! Feel free to open issues or create pull requests to improve this task management application.

## License
This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

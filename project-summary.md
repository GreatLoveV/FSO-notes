# FSO-notes Project Summary

This project is a simple note-taking application built with React.

## Core Functionality

*   **View Notes:** Displays a list of notes fetched from a backend API.
*   **Add Notes:** Users can add new notes through a form.
*   **Toggle Importance:** Users can mark notes as important or not important.
*   **Filter Notes:** Users can filter notes to show all notes or only important ones.
*   **User Authentication:** The application supports user login. Users need to be logged in to add notes.
*   **Error Handling:** Displays error messages for events like failed login or trying to update a deleted note.
*   **Persistence:** The logged-in user's information is stored in the browser's local storage to maintain the session across page reloads.

## Components

*   **`App.jsx`**: The main component that manages the application's state and logic.
*   **`Note.jsx`**: A component that renders a single note.
*   **`Footer.jsx`**: A component that displays the application's footer.
*   **`Notification.jsx`**: A component for displaying error messages.
*   **`Login.jsx`**: A component that was started but is not used, the login form is rendered from `App.jsx`
*   **`login.js`**: A service module for handling login API calls.
*   **`notes.js`**: A service module for handling API calls related to notes (fetching, creating, updating).

## State Management

The application uses React's `useState` and `useEffect` hooks to manage its state, including the list of notes, user input, and authentication status.

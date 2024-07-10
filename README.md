# Bookstore MERN Project

This project is a full-stack MERN (MongoDB, Express.js, React.js, Node.js) application for managing a bookstore.

## Features Implemented

- **View Books**: Display a list of books either in a table or card view.
- **Create Book**: Add new books with title, author, and publish year.
- **Edit Book**: Modify existing book details including title, author, and publish year.
- **Delete Book**: Remove a book from the database.
- **Show Book**: Display detailed information about a specific book, including its ID, title, author, publish year, creation time, and last update time.

## Components

### Home Component

The `Home` component displays a list of books either in a table or card format. It fetches data from the server and allows users to switch between different views.

### CreateBook Component

The `CreateBook` component enables users to add new books to the database. It includes form fields for entering book details and handles the submission using Axios for HTTP requests.

### EditBook Component

The `EditBook` component allows users to modify existing book details. It pre-fills form fields with current book data fetched from the server using Axios. Users can update the details and save changes back to the database.

### DeleteBook Component

The `DeleteBook` component prompts users to confirm deletion of a book. It sends a DELETE request to the server using Axios upon confirmation and notifies the user with a Snackbar message upon successful deletion.

### ShowBook Component

The `ShowBook` component fetches and displays detailed information about a specific book identified by its ID. It includes fields for ID, title, author, publish year, creation time, and last update time. The information is fetched using Axios and displayed conditionally based on loading state.

## Technologies Used

- **Frontend**: React.js, Axios for HTTP requests, React Router for navigation, Notistack for Snackbar notifications.
- **Backend**: Node.js, Express.js for server-side logic, MongoDB for data storage.
- **Styling**: Tailwind CSS for styling components.

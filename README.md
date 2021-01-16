React Google Books Search

Overview:

React-based Google Books Search app. This Single Page Application uses [`react-router-dom`]to navigate, hide and show your React components without changing the route within Express. Using helper/util functions and React lifecycle methods to query and display books based on user searches, this is a full MERN stack application which allows users to save books to a database to refer to at a later date. Built with Node, Express and MongoDB, and React-Toastify for custom alerts.

 required npm packages:

`mongoose`, `axios`, `react-router-dom`, `react-toastify`

The Database used:

1. Connect to a MongoDB database named `googlebooks` using the mongoose npm package.

2. Using mongoose, create a Book schema.

3. Books should have each of the following fields:

* `title` - Title of the book from the Google Books API

* `authors` - The books's author(s) as returned from the Google Books API

* `description` - The book's description as returned from the Google Books API

* `image` - The Book's thumbnail image as returned from the Google Books API

* `link` - The Book's information link as returned from the Google Books API

Technologies Used:
* Express
* Node.js
* Bootstrap
* MongoDB
* Heroku
* React


Link to App:

 https://lil-google-books-search.herokuapp.com/



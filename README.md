# BookStore Management System

## Overview

The **BookStore Management System** is a simple web-based application built using **Node.js** that allows users to manage books through a REST-style API and a basic frontend. The project demonstrates CRUD operations, client–server interaction, and API integration using JavaScript.

This system is suitable for academic projects and learning full-stack JavaScript fundamentals.

## Features

* Add new books
* View list of available books
* Backend API for book operations
* Frontend pages for listing and adding books
* JSON-based data handling

## Tech Stack

* **Backend:** Node.js, Express.js
* **Frontend:** HTML, JavaScript
* **API Style:** REST
* **Package Manager:** npm

## Project Structure

```
BookStore-Management-System/
│── node_modules/
│── book-api.js        # Backend API (Express server)
│── book-list.html     # Book listing UI
│── book-list.js       # Frontend logic for listing books
│── new-book.html      # Add new book UI
│── package.json       # Project metadata and dependencies
│── package-lock.json  # Dependency lock file
```

## Installation & Setup

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd BookStore-Management-System
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the server:

   ```bash
   node book-api.js
   ```

4. Open the frontend:

   * Open `book-list.html` in a browser to view books
   * Open `new-book.html` to add a new book

## API Overview

| Method | Endpoint | Description     |
| ------ | -------- | --------------- |
| GET    | /books   | Fetch all books |
| POST   | /books   | Add a new book  |

*(Endpoints may vary based on implementation in `book-api.js`)*

## Usage

* Run the Node.js server
* Use the frontend pages to interact with the API
* Books can be added and viewed dynamically

## Future Enhancements

* Database integration (MongoDB / MySQL)
* Update & delete book functionality
* Better UI styling
* Input validation
* Deployment on cloud (Render / Vercel)

## Conclusion

This BookStore Management System demonstrates a basic full-stack JavaScript application using Node.js and REST APIs. It serves as a strong foundation for more advanced bookstore or inventory management systems.

## Author

Prathmesh Balsurkar

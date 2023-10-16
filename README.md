# Library
This application serves as a demo for a library system built using the PERN stack. Users can browse books, check availability, and manage their borrowings.

## Technologies Used:
- PostgreSQL
- Express.js
- React.js
- Node.js
- [List any other dependencies or libraries here]

## Setup and Installation:
1. Clone the repository.
2. Navigate to the project directory.
3. Install dependencies using `npm install`.
4. Set up the PostgreSQL database.
5. Start the server using `npm start`.

## API Documentation:

### GET /books
Fetches a list of all books.

### POST /book
Adds a new book.
- Request Body: 
  - `title`: Title of the book.
  - `author`: Author of the book.
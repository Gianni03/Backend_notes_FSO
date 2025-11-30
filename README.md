# Backend_notes_FSO

the site is live here: https://backend-notes-fso-tmi3.onrender.com


This is the backend for the notes app in the Full Stack Open course
It is built with Node.js and Express.js
It provides a RESTful API for managing notes, including creating, reading, updating, and deleting notes.
The backend uses an in-memory array to store notes for simplicity.
To run the backend locally, follow these steps:
1. Clone the repository:
   git clone <repository_url>
2. Navigate to the project directory:
   cd backend_notes_fso
3. Install the dependencies:
   npm install
4. Start the server:
   npm start
The server will start on http://localhost:3001 by default.
You can use tools like Postman or curl to interact with the API endpoints.
API Endpoints:
- GET /api/notes: Retrieve all notes.
- GET /api/notes/:id: Retrieve a specific note by ID.
- POST /api/notes: Create a new note.
- PUT /api/notes/:id: Update an existing note by ID.
- DELETE /api/notes/:id: Delete a note by ID.
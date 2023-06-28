# NoteStack
NoteStack is a web application built using MongoDB, Node.js, EJS, CSS, and JavaScript. It provides a convenient platform for users to take notes, with features such as adding new notes, editing existing notes, deleting notes, and searching for notes using keywords.

## Features

- Google Authentication: Users can sign in and sign up using their Google accounts, ensuring a secure and personalized experience.
- Add New Note: Users can create and save new notes, capturing their thoughts, ideas, and important information.
- Edit Existing Note: Users can easily edit and update their existing notes, allowing them to refine and organize their content.
- Delete Note: Users have the option to delete unwanted or outdated notes, keeping their workspace clean and clutter-free.
- Search Notes: The app provides a powerful search functionality, enabling users to find specific notes by searching for keywords used within the notes.

## Technologies Used

- MongoDB: A flexible and scalable NoSQL database used for storing and retrieving note data.
- Node.js: A JavaScript runtime environment that powers the server-side logic of the application.
- EJS: A templating language for generating dynamic HTML content.
- CSS: Cascading Style Sheets used for styling the website and enhancing the user interface.
- JavaScript: The programming language used for client-side interactivity and functionality.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/2912anushka/NoteStack.git
```

2. Install the dependencies:

```bash
cd notestack
npm install
```

3. Set up environment variables:

   - Create a `.env` file in the root directory.
   - Add the following environment variables and provide their respective values:

   ```bash
   GOOGLE_CLIENT_ID=your_google_client_id
   GOOGLE_CLIENT_SECRET=your_google_client_secret
   MONGODB_URI=your_mongodb_uri
   GOOGLE_CALLBACK_URL=http://localhost:5000/google/callback
   ```

4. Start the application:

```bash
npm start
```

5. Open your web browser and visit `http://localhost:5000` to access the NoteStack website app.

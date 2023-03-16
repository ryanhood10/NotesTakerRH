# Note Taker
Note Taker is a simple web application built with Express.js that allows users to create and manage notes. When you click "Get Started" on the home page, you're presented with a screen where you can add a note, and save it into the notes list. You can also delete notes on the list by pressing the trashcan icon.

## Functionality
The application has the following functionality:

Allows users to add new notes with a title and a text body.
Saves notes to a list of existing notes.
Allows users to delete notes from the list.
## Installation
To use the Note Taker application, you'll need to have Node.js and npm installed on your computer. You can install them from the official Node.js website.

After installing Node.js and npm, you can install the application's dependencies by running the following command in the application's terminal:

Copy code
npm install
This will install the required packages, including Express.js.

## Usage
To start the Note Taker application, run the following command in the application's terminal:

sql
Copy code
npm start
This will start the application and listen for incoming requests on port 3000.

To use the application, open your web browser and go to http://localhost:3000. Click "Get Started" to go to the notes page, where you can view existing notes and create new ones. To create a new note, click the "Note Title" and "Note Text" fields and enter your note's information. Then click the save icon in the top-right corner of the panel to save the note. The new note will be added to the list of existing notes on the left side of the page. To delete a note, click the red trash icon next to the note you want to delete. This will remove the note from the list of existing notes.

- an alternative option wouold be to open the application at https://notestakerapp14.herokuapp.com/

## Deployment
The Note Taker application has been deployed on Heroku and is available for use. To access the deployed application, go to the following URL:

php
Copy code
<heroku-url>
The application uses the same functionality as described above. The application uses the process.env.PORT environment variable to listen to incoming requests on the assigned Heroku port. The application's dependencies are automatically installed when deployed to Heroku.

## Technologies Used
The Note Taker application was built with the following technologies:

Node.js
Express.js
## Credits
  Ryan Hood github.com/ryanhood10

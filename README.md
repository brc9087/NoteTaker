<h1>NoteTaker Application<h1>

-This NoteTaker Application application can be used to write, save, and delete notes. This application will use an express backend and save and retrieve note data from a JSON file.
<br>
-A user will be able to write and save notes.
<br>
-A user will be able to delete notes written before.
<br>
-A user will be able able organize their thoughts and keep track of tasks that need to be completed.
<br>
-For users that need to keep track of a lot of information, it's easy to forget or be unable to recall something important. Being able to take persistent notes allows users to have written information available when needed.
<br>
<h4>Steps to use app </h4>
<br>
1. on home page - click on get started button
<br>
2. on the notes page type in a "title" for your note under the "title" text area 
<br>
3. Under the "note text" text area, type in desired note.
<br>
<br>

<h4>Server.js File</h4>
<br>
-The server.js file serves as the gatekeeper to open the port (8080) and link the APIRoutes.js file by 'requiring' it.
-Activate the port by app.listen
-once open and listening it console logs "App listening on PORT: 8080"
<br>
<br>

<h4> APIRoute.js / DB.json File</h4>
<br>
-fs and path are required as dependancies
<br>
-module.exports allows files to be linked and able to communicate amonst each other.
<br>
-fs.readfile allows the db.json file to interpret incoming data from POST. 
<br>
-app.get allows the user to "get" information from posted data. 
<br>

<h4> Links to Notetaker App / Github Page </h4>
<a href="https://mighty-headland-17179.herokuapp.com/">NoteTaker App</a>
<a href="https://github.com/brc9087/NoteTaker"</a>

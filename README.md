<h3>NoteTaker Application<h3>
<br>
<p>-This NoteTaker Application application can be used to write, save, and delete notes. This application will use an express backend and save and retrieve note data from a JSON file.</p>
<br>
<p>-A user will be able to write and save notes. </p>
<br>
<p>-A user will be able to delete notes written before. </p>
<br>
<p>-A user will be able able organize their thoughts and keep track of tasks that need to be completed.</p>
<br>
<p>-For users that need to keep track of a lot of information, it's easy to forget or be unable to recall something important. Being able to take persistent notes allows users to have written information available when needed. </p>
<br>
<h4>Steps to use app </h4>
<br>
<p>1. on home page - click on get started button</p>
<br>
<p>2. on the notes page type in a "title" for your note under the "title" text area </p>
<br>
<p>3. Under the "note text" text area, type in desired note.</p>
<br>
<br>

<h4>Server.js File</h4>
<br>
<p>-The server.js file serves as the gatekeeper to open the port (8080) and link the APIRoutes.js file by 'requiring' it.</p>
<p>-Activate the port by app.listen</p>
<p>-once open and listening it console logs "App listening on PORT: 8080"</p>
<br>
<br>

<h4> APIRoute.js / DB.json File</h4>
<br>
<p>-fs and path are required as dependancies</p>
<br>
<p>-module.exports allows files to be linked and able to communicate amonst each other.</p>
<br>
<p>-fs.readfile allows the db.json file to interpret incoming data from POST. </p>
<br>
<p>-app.get allows the user to "get" information from posted data. </p>
<br>

<h4> Links to Notetaker App / Github Page </h4>
<a href="https://mighty-headland-17179.herokuapp.com/">NoteTaker App</a>
<a href="https://github.com/brc9087/NoteTaker"> Github Page</a>

# Express.js -- Note-Taker



# Express.js: Note Taking Application (Week 11 Challenge)

## Summary of Task

This week my task was to modify starter code to create an application called Note Taker that can be used to write and save notes. This application uses an Express.js back end and saves and retrieves note data from a JSON file.

The application’s front end was already created. It was my job to build the back end, connect the two, and then deploy the entire application to Render.

Below are the following Challenge requirements according to the 

**User Story** & **Acceptance Criteria**

## User Story

```md
AS A small business owner
I WANT to be able to write and save notes
SO THAT I can organize my thoughts and keep track of tasks I need to complete
```

## Acceptance Criteria


```md
GIVEN a note-taking application
WHEN I open the Note Taker
THEN I am presented with a landing page with a link to a notes page
WHEN I click on the link to the notes page
THEN I am presented with a page with existing notes listed in the left-hand column, plus empty fields to enter a new note title and the note’s text in the right-hand column
WHEN I enter a new note title and the note’s text
THEN a "Save Note" button and a "Clear Form" button appear in the navigation at the top of the page
WHEN I click on the Save button
THEN the new note I have entered is saved and appears in the left-hand column with the other existing notes and the buttons in the navigation disappear
WHEN I click on an existing note in the list in the left-hand column
THEN that note appears in the right-hand column and a "New Note" button appears in the navigation
WHEN I click on the "New Note" button in the navigation at the top of the page
THEN I am presented with empty fields to enter a new note title and the note’s text in the right-hand column and the button disappears
```


## Additional Requirements

On the back end, the application includes a `db.json` file that is used to store and retrieve notes using the `fs` module.

The following HTML routes were created:

* `GET /notes` to return the `notes.html` file.

* `GET *` to return the `index.html` file.

The following API routes were also created:

* `GET /api/notes` to read the `db.json` file and return all saved notes as JSON.

* `POST /api/notes` to receive a new note to save on the request body, add it to the `db.json` file, and then return the new note to the client. 

I also added the DELETE route to the application using the following guideline:

* `DELETE /api/notes/:id` should receive a query parameter that contains the id of a note to delete. To delete a note, you'll need to read all notes from the `db.json` file, remove the note with the given `id` property, and then rewrite the notes to the `db.json` file.


## Project View

![Note Taker Main Page](<Develop/assets/images/Note Taker Main Page Screenshot.jpg>)

![Notes List](<Develop/assets/images/Note List Screenshot.jpg>)

## Contact Information
Thanks for visiting!

If you would like to learn more, or contact me, feel free to reach me at the following:

<ul>
    <li>Render URL:  </li>
    <li>GitHub URL: https://github.com/mandrade09/Express.js_Note-Taker </li>
    <li>E-mail: mattandrade09@gmail.com </li>
    <li>Phone: 310.903.9150</li>
</ul>

<p>
<footer> &ndash; Matthew Andrade</footer>
</p>

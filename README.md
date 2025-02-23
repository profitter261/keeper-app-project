# keeper-app-project
keeper app project
This Keeper App is a simple note-taking application built using HTML, CSS, and JavaScript. It allows users to add and delete notes dynamically, making it a basic yet functional tool for jotting down quick ideas or reminders.

The HTML structure consists of an input field where users can type their notes, a button labeled "Add" to save the note, and a div element where the notes will be displayed. Each note appears inside a separate div, along with a delete button to remove it when needed.

The CSS styling gives the app a neat and user-friendly appearance. The background is light-colored, while the note container has a white background with a shadow effect and rounded corners for a clean look. Each note is designed to resemble a sticky note with a yellow background, and the delete button is styled in red for easy identification.

The JavaScript functionality powers the app's interactivity. When a user types a note and clicks the "Add" button, the addNote() function is triggered. It retrieves the input value, creates a new note element, appends it to the display area, and then clears the input field. Each note includes a delete button, which, when clicked, triggers the deleteNote() function, removing the corresponding note from the display.

This project can be further enhanced by implementing Local Storage to save notes even after the page is refreshed. Additional features like an edit option, drag-and-drop reordering, and dark mode could also improve the usability and experience. Let me know if you need any modifications or additional features!

**How the App Works**
1) User enters a title and content.
2) Clicks Add, and the note appears below.
3) Can delete a note anytime by clicking the X button.

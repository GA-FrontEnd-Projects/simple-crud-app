# Simple CRUD app

We'll be creating a simple CRUD create, read, update, delete) application to help simulate what a real-world development project might look like.

We will be building a simple to-do list application that allows us to create to-do list items, update them, reorder them, and delete them, all on the front end. You can optionally add back end technology once you feel like your front end is in good shape.


## Data Storage

Since we'll be dealing with a number of "records" (our to-do list items), we'll need somewhere to store them. We have a couple of options for where we can do that:

1) JavaScript objects

2) Cookies

3) LocalStorage  

Note that only cookies and LocalStorage will allow our data to persist after a page reloads.

Keep your records in a JavaScript object to start, and you can experiment with the other storage methods after you get the app working reliably.

Each record should have the following attributes:

<code>id</code>
<code>isComplete</code>
<code>title</code>
<code>order</code>
<code>creationDate</code>


## App Structure

Our app should consist of one HTML file (index.html), one stylesheet file (style.css) and probably two JavaScript files, one that contains your app code (script.js) and one that contains the initial state of your "database" (seed-data.js).


## App Layout

The layout of the page can be whatever you like, but you'll need, at minimum, a table where the records will be displayed with labels for the columns of the table, and a button for adding new records. Each record should display the title of the task, whether it's been completed, and the date it was added. There should also be buttons for editing and deleting the record. Lastly, you'll need a form for creating the record and another form for editing a record.


## App Behavior

Here's what the app should do:

1) When the user first loads the page, the list of to-do items should appear on the page, matching what's in the "database".

2) When someone clicks the "add record" button, a new record should be added to the HTML list using default (hard-coded or slightly randomized) information. A new record should also be added to the "database".

3) When someone clicks the "delete" button next to a record, that record will removed from the list of items in the HTML. That record should also be removed from the "database".

4) When someone clicks the "edit" button next to a record, a form should appear, populated with the existing information for that record.

5) When that form is saved, the HTML and the "database" of the appropriate record with the edited information shoud be updated.


## Helpful Resources

Here are some resources that will make your styling and some of your interactions much easier:

1) [Twitter Bootstrap](http://getbootstrap.com/)

2) [Handlebars.js](http://handlebarsjs.com/)

3) [FontAwesome](http://fontawesome.io/)

4) [jQuery](https://jquery.com/)

5) [jQuery UI](http://jqueryui.com/)
CRUD

Create
Read
Update
Delete

Model specs
	id
	isComplete
	title
	order
	creationDate

Behaviors
	When the user first loads the page, the list of to-do items should appear on the page, matching what's in the "database"
	When someone clicks the "add record" button, a new record should be added to the HTML list using default information
		A new record should be added to the "database", as well
	When someone clicks the "delete" button next to a record, that record will removed from the list of items
		That record should be removed from the "database"
	When someone clicks the "edit" button next to a record, a form should appear, populated with the existing information for that record



The place where the data goes?
	JavaScript Objects - Not persistent
	Cookies - Persistent
	LocalStorage - Persistent
	
To-do list UI
	"Add record" button
	Delete button (per record)
	An edit button (per record)
	Form for creating To-do list items
	Form for updating the To-do list item
	
Layout
	List of records
	A header above the list of records which contains the add button
	Labels for columns

Helpful resources
	Twitter bootstrap
	FontAwesome
	jQuery
	jQuery UI
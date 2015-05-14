#CatchPhrase.ly

Let's build an app for our favorite game **Catchphrase**!

This lab will span over the course of several days. The suggested workflow for each day is outlined below. We will wrap up our work on 5/18.
	
##Day 1 - Get & Render
Reference lesson: [Underscore templating](https://github.com/sf-wdi-18/notes/tree/master/lectures/week-03/day_3_todo_ajax/dawn_templating)

###User Stories
**A User should see a list of existing `phrases` on the home page**

* A phrase object should have the properties: `id`, `word`, & `definition`

* The app should hold an array of hard-coded phrases. This will serves as our "database". (You will need to make a few up!)

###General Guidelines
* Start an express project with all the necessary requirements
* Create an index (home) page
* Serve up your static assets (html, css, js) in a public directory
* Your '/phrases' route should return phrases as JSON
* Use AJAX to GET phrases
* Render the phrases on the index page using underscore templating

<br><br><br><br>

##Day 2 - Post & Delete
Reference lesson: [Single Page POST & DELETE](https://github.com/sf-wdi-18/notes/blob/master/lectures%2Fweek-03%2Fday_3_todo_ajax%2Fdusk%2FREADME.md)

###User Stories
**A User should be able to create a new phrase by submitting a form**

* The DOM should maintain state accordingly

* The phrase should persist with a page refresh

**A User should be able to delete any phrase**

* The DOM should update accordingly
	
* The removed phrase should remain removed upon a page refresh

###General Guidelines

* Create a form for the user to add a new catchphrase
* Send an AJAX POST with form data - if the post is successful, update the view
* Add a delete button next to each catchphrase. When a user clicks the button, delete the corresponding phrase from the backend (the ids should match). If the delete is successful, update the view.

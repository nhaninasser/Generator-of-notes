# Note
Note-Taker

# Purpose
A note taker built using Express.js.  Allows the user to input a note on the right, which will then save on the server to the left, each individual note having a unqiue ID in the db.json, which will allow the user the ability to delete the item, based upon the said ID in the backend.  

# User Story
AS A small business owner
I WANT to be able to write and save notes
SO THAT I can organize my thoughts and keep track of tasks I need to complete

# Acceptance Criteria
- GIVEN a note-taking application
- WHEN I open the Note Taker
- THEN I am presented with a landing page with a link to a notes page
- WHEN I click on the link to the notes page
- THEN I am presented with a page with existing notes listed in the left-hand column, plus empty fields to enter a new note title and the note’s text in the right-hand column
- WHEN I enter a new note title and the note’s text
- THEN a Save icon appears in the navigation at the top of the page
- WHEN I click on the Save icon
- THEN the new note I have entered is saved and appears in the left-hand column with the other existing notes
- WHEN I click on an existing note in the list in the left-hand column
- THEN that note appears in the right-hand column
- WHEN I click on the Write icon in the navigation at the top of the page
- THEN I am presented with empty fields to enter a new note title and the note’s text in the right-hand column

# Struggles Encountered
Took me a long time to get everything working the way I wanted it too. Would need more time to figure out the delete button!

# Usage :

* Clone this repository to use this application on local machine.

* To install necessary dependencies, run the following command :

```
npm i
```

* The application will be invoked with the following command: This will start localhost server on PORT 3000.

```
node server.js
```

* Open browser and type `http://localhost:3000/` to run this application on your local machine.


# Screenshots
![SS1](https://user-images.githubusercontent.com/93559764/153790719-e564a6f2-b3ed-4ce2-9219-0dc9386ad968.jpeg)
![SS2](https://user-images.githubusercontent.com/93559764/153790789-e95da807-0fd0-4b3b-9c4e-971eb0219690.png)

# Demo 
![TutorialVideo](https://user-images.githubusercontent.com/93559764/153790922-430f0342-9bca-4f96-8529-5f0266719a33.gif))

# Made With
* HTML
* CSS
* JS
* Node.js
* Express.js

# Heroku deployed link
https://calm-woodland-64121.herokuapp.com/

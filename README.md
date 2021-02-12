#### Hosted at https://github.com/frenchy0943/bootcampSBA1
# Technical Specifications
### Overview
- Use of Bootstrap to make the layout of each page similar
- The login page uses forms and regex to verify that the email address entered is in the correct format
- Couldn't get the password verification to work so as of now no password is needed to enter, just a valid email
- The home page takes advantage of bootsraps grid system to have the games evenly spread across the page
- It uses forms for the input given by the user in the form of a drop down select menu. 
- That info is then passed to the JS when the user clicks submit
- The JS for that page looks at the ratings for each game and sorts the games into array based on highest rating
- The array is then looped through and a seperate h5 element is made for each game to make them block elements as they are printed on to the home page in the correct order
- The about us page is makes use of the table to have names and contact information on them for the "team members"
### HTML
- div
- h1
- h4
- a
- h3
- p
- form
- label
- select
- option
- button
- img
- input
- h2
- table
- tr
- th
- td
### CSS
- Multiple uses of all styling options (inline, internal, external)
- Selectors: body, label, h3, h2, tr > td, custom classes and ids
### Javascript
- Use of external sheets
- variables, if statements, for loop, collection used in form of getElementById and store of data in an array, events used with onclick, and fucntions to collect data, sort the data, and print it back to the user 
# Description
### First page 
- Login page, containing a input for email and password.
- Email is checked to see if its a valid format for an email address
- Once you've logged in you're sent to the home page
### Home Page
- Here you can rate three different games on a scale of 1 to 10 through drop down menus
- If you haven't played the games you can select N/A
- A list will then be printed with the name of the games in order from highest rating to lowest rating
- There is a link at the top of the page which takes you to the About Us page
### About Us Page
- Here there is a small paragraph explaining the website and why it might be used
- There is also a table which has the names of the team members and how to contact them
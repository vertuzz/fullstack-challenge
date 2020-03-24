# Enodo Fullstack Challenge

Welcome to our Fullstack Challenge repository. This README will guide you on how to participate in this challenge.

Please fork this repo before you start working on the challenge. We will evaluate the code on the fork.


## Challenge


Front-end and backend to allow users to search, select, or unselect properties from the DB.

## Requirements
- Frontend with Element.js and Vue.js
- DB with data from excel file (suggestion: Sqlite)
- API (suggestion: falcon, flask, express...)
- Input field with [autocomplete](https://element.eleme.io/#/en-US/component/input#autocomplete), displaying the properties from the DB through the API.
  - On Selection of search result save as "Selected" to DB.
- Table Showing selected properties:
  - Column 1: Full Address
  - Column 2: Class Description
  - Column 3: Delete button
- Delete button unselect property from DB.
- One of the following:
  - Option 1: [Google Maps](https://developers.google.com/maps/documentation/javascript/get-api-key) that display the selected properties
  - Option 2: Add test to your implementation (Suggestion: Jest).
- A Readme on how to run your solution.
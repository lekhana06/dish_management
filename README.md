This a full stack project.
It contains following tasks:

1. database creation:

- A database schema designed to store dishes with the following fields:
- `dishId` (unique identifier)
- `dishName` (string)
- `imageUrl` (string)
- `isPublished` (boolean)

I have used mongo db server.
I have created db in the dishesDB.Under that we have to create a collection dishes and the data is stored in that collection.

- .env.local file- contains the username and password of the database
- app/lib/db.js - It has the connection string for the database connection. We have paste our password there.
- app/lib/dishesModel.js - here we create a database model and schema

2. API Development

- Created an API to fetch the list of dishes from the database. API endpoint in my project is "http://localhost:3000/api/dishes"
- Created an API to toggle the `isPublished` status of a dish. API endpoint in my project is "http://localhost:3000/api/togglePublish"

3. Front-End Dashboard

- Display all dishes with their information.
- Has a button to toggle the published status, updating both the UI and backend.
"# dish_mangement" 
"# dish_mangement" 

SETUP AND REQUIRED DEPENDENCIES
------> npm init -y
------> npm install express


To test and update your REST API using Postman,

Step: 1 Start your Server "node index.js"

Step: 2 Testing Endpoints in Postman

    1. GET All Items
    Method: GET
    URL: http://localhost:3000/api/items


    2. GET a Single Item by ID
    Method: GET
    URL: http://localhost:3000/api/items/1 (replace 1 with the desired item ID)

    3. POST a New Item
    Method: POST
    URL: http://localhost:3000/api/items
    Body: JSON(select raw and json format)
    {
        "name": "New Item"
    }

    ID will automatically increment

    4. PUT to Update an Item by ID
    Method: PUT
    URL: http://localhost:3000/api/items/1 (replace 1 with the desired item ID)
    Body: JSON(select raw and json format)
    {
        "name": "Updated Item"
    }

    5. DELETE an Item by ID
    Method: DELETE
    URL: http://localhost:3000/api/items/1 (replace 1 with the desired item ID)
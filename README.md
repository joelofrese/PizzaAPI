# Pizza Inventory RESTful API, .NET

This RESTful API is designed to manage a pizza inventory. It provides various endpoints for interacting with pizza data, including retrieving a list of all pizzas, getting a pizza by its ID, adding a new pizza, updating an existing pizza, and deleting a pizza.

## Endpoints

- **GET /Pizza**: Get a list of all pizzas.

- **GET /Pizza/{id}**: Get a pizza by its ID. Replace `{id}` with the actual pizza ID.

- **POST /Pizza**: Add a new pizza. Provide the pizza data in the request body.

- **PUT /Pizza/{id}**: Update an existing pizza by its ID. Replace `{id}` with the actual pizza ID and provide the updated pizza data in the request body.

- **DELETE /Pizza/{id}**: Delete a pizza by its ID. Replace `{id}` with the actual pizza ID.

## Example Usage

Here are some example use cases for each endpoint:

### Get a List of All Pizzas

- **Request**: GET /Pizza
- **Response**: Retrieve a JSON array containing all the pizzas in the inventory.

### Get a Pizza by ID

- **Request**: GET /Pizza/{id}
- **Response**: Retrieve a JSON object representing the pizza with the specified ID.

### Add a New Pizza

- **Request**: POST /Pizza
  - Provide pizza data in the request body (e.g., name, description, price).
- **Response**: The newly added pizza is created and returned in the response.

### Update an Existing Pizza

- **Request**: PUT /Pizza/{id}
  - Replace `{id}` with the pizza's ID.
  - Provide the updated pizza data in the request body.
- **Response**: The pizza with the specified ID is updated.

### Delete a Pizza

- **Request**: DELETE /Pizza/{id}
  - Replace `{id}` with the pizza's ID.
- **Response**: The pizza with the specified ID is deleted from the inventory.

## How to Use

1. Clone this repository or integrate the API into your .NET project.
2. Make sure you have the required dependencies and packages installed.
3. Run the application.
4. Use your preferred API testing tool (e.g., Postman) to interact with the API using the provided endpoints.


Enjoy your pizza! 🍕

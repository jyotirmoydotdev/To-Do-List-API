# To-Do List API

This is a simple RESTful API for managing a to-do list. It allows you to create, read, update, and delete to-do items. The API is built using the Gin framework for Go.

## Getting Started

### Prerequisites

Before you start, make sure you have the following installed:

- Go (Golang)
- Gin (Gin-Gonic framework)

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/jyotirmoydotdev/To-Do-List-API.git
   ```

2. Change to the project directory:

   ```bash
   cd To-Do-List-API
   ```

3. Build and run the application:

   ```bash
   go run main.go
   ```

The API will start running on `http://localhost:9090`.

## API Endpoints

### Get All To-Do Items

- **URL:** `/todos`
- **Method:** `GET`
- **Response:** List of all to-do items.

### Get a Single To-Do Item

- **URL:** `/todos/:id`
- **Method:** `GET`
- **Parameters:**
  - `id` (string) - The unique identifier of the to-do item.
- **Response:** Details of the specified to-do item.

### Create a To-Do Item

- **URL:** `/todos`
- **Method:** `POST`
- **Request Body:** JSON object with the following fields:
  - `title` (string) - The title or description of the to-do item.
- **Response:** Details of the newly created to-do item.

### Update To-Do Item Status

- **URL:** `/todos/:id`
- **Method:** `PATCH`
- **Parameters:**
  - `id` (string) - The unique identifier of the to-do item.
- **Response:** Updated details of the to-do item with toggled status (completed/uncompleted).

### Delete a To-Do Item

- **URL:** `/todos/:id`
- **Method:** `DELETE`
- **Parameters:**
  - `id` (string) - The unique identifier of the to-do item.
- **Response:** A success message if the item was deleted successfully.

### Reset To-Do List

- **URL:** `/todos/reset`
- **Method:** `DELETE`
- **Response:** A success message indicating that the entire to-do list has been reset.

## Usage

You can interact with this API using your preferred REST client (e.g., Postman, curl) or integrate it into your own applications.

## Contributing

Contributions to this project are welcome. You can submit bug reports, feature requests, or even pull requests to help improve the functionality and documentation.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Follow Me on Twitter

Stay updated with the latest tech trends, coding tips, and more by following me on Twitter [@jyotirmoydotdev](https://twitter.com/jyotirmoydotdev). Feel free to reach out, ask questions, or engage in discussions related to programming, development, and technology. I look forward to connecting with you!

[![Follow me on Twitter](https://img.shields.io/twitter/follow/jyotirmoydotdev?style=social)](https://twitter.com/jyotirmoydotdev)
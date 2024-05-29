# Bookshelf API

Bookshelf API is a RESTful API project for managing books using Hapi.js and ESLint for code linting.


## Precondition

Before running this project, make sure you have installed:

- Node.js

## Steps to Execute the Project

1. **Clone this repository**:

    ```sh
    git clone https://github.com/TearsAchly/Bookshelf-API.git
    cd Bookshelf-API
    ```

2. **Install dependencies**:

    ```sh
    npm install
    ```

3. **Run server**:

    ```sh
    npm start
    ```

4. **Linting code**:

    To ensure your code is free from linting issues, run:

    ```sh
    npx eslint .
    ```

## Directory Structure

- **Bookshelf API Test**: Directory containing Postman collections and environments for API testing.
- **eslint.config.mjs**: ESLint configuration.
- **package.json**: Npm configuration file.
- **src**: Directory containing project source files.
  - **books.js**: File containing book data.
  - **handler.js**: File containing the handler for handling requests.
  - **routes.js**: File containing API route definitions.
  - **server.js**: The main file for running the Hapi.js server.

## Endpoints

- **Books**
    - `POST /books`: Adds new books.
    - `GET /books`: Gets a list of books.
    - `GET /books/{id}`: Get book details.
    - `PUT /books/{id}`: Updates books.
    - `DELETE /books/{id}`: Deletes a book.

## Testing with Postman

You can test APIs using Postman by importing collections and environments located in the `Bookshelf API Test` directory.

1. **Open Postman**.
2. **Import collections and environments**:
    - Collection: `Bookshelf API Test.postman_collection.json`
    - Environment: `Bookshelf API Test.postman_environment.json`
3. **Run the test using the imported collection**.

## Contribution

Please open a pull request or submit an issue to contribute to this project.

## Licence

This project is licensed under the MIT license. See the [LICENSE](LICENSE) file for more information.

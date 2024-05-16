# Book Library
### API Gateway with SQLite, Express, and Apollo Server

This repository showcases an API gateway implementation using Node.js with SQLite as the database, Express as the web application framework, and Apollo Server as the GraphQL server. It serves as a centralized entry point for various microservices, offering a unified API for clients.

#### Features
- GraphQL API powered by Apollo Server
- SQLite database for storing books and stories
- REST endpoints for querying and manipulating books and stories
- Integration with gRPC client for remote services (books and stories)
- Cross-Origin Resource Sharing (CORS) support
- Request body parsing using body-parser

#### Installation
**Clone the repository:**
```bash
git clone https://github.com/your-username/api-gateway.git
cd api-gateway
```
**Install the dependencies:**
```bash
npm install
```
**Start the server:**
```bash
npm start
```
The API gateway will be accessible at [http://localhost:3000](http://localhost:3000).

#### Usage
The API gateway provides the following endpoints:

- **GET /books:** Retrieve all books.
- **GET /books/:id:** Retrieve a specific book by ID.
- **POST /book:** Create a new book.
- **GET /stories:** Retrieve all stories.
- **GET /stories/:id:** Retrieve a specific story by ID.
- **POST /story:** Create a new story.

The GraphQL API is available at [http://localhost:3000/graphql](http://localhost:3000/graphql) and can be accessed using tools like GraphQL Playground or Postman.

#### Configuration
The API gateway's configuration can be adjusted by modifying the following files:

- **book.proto:** Protocol Buffers file defining the gRPC service and message definitions for books.
- **story.proto:** Protocol Buffers file defining the gRPC service and message definitions for stories.
- **resolvers.js:** Houses the resolver functions for GraphQL queries and mutations.
- **schema.js:** Defines the GraphQL schema using the GraphQL Schema Definition Language (SDL).

#### Contributing
Contributions are encouraged! If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request.

#### License
This project is licensed under the MIT License. See the LICENSE file for more details.

Feel free to tailor the description to your liking and include any additional pertinent information about the project.

# Discussing REST Architecture in Detail

REST (Representational State Transfer) is a way of building web services that allow systems to communicate over the internet. It is based on a client-server model where the client sends requests, and the server responds with data. REST is popular because it uses simple and well-known technologies like HTTP.

### Principles of REST

1. **Client-Server Architecture**: The client and server are separate. The client is responsible for the user interface, and the server handles the data.
2. **Statelessness**: Each request from the client contains all the information needed. The server does not store any information about previous requests.
3. **Cacheability**: Responses from the server can be cached to make future requests faster.
4. **Uniform Interface**: All interactions between the client and server follow the same rules, which makes it easier to understand and use.
5. **Layered System**: The system can be divided into layers, like proxies or gateways, without changing how the client and server interact.

### HTTP Methods in REST

In REST, the client uses standard HTTP methods to interact with the server:

* **GET**: Retrieves data from the server (e.g., information about books).
* **POST**: Sends data to the server to create a new resource (e.g., adding a new book).
* **PUT**: Updates an existing resource on the server (e.g., changing a book's details).
* **DELETE**: Removes a resource from the server (e.g., deleting a book).
* **PATCH**: Partially updates a resource (e.g., changing only the title of a book).

### Advantages of REST

- **Easy to Use**: REST uses standard HTTP methods that are familiar to most developers.
- **Scalable**: Because each request is independent, it is easier to scale REST services.
- **Flexible**: REST can be used with any programming language and is not limited to a specific platform.
- **Performance**: Responses can be cached, which improves the speed of requests.

### Real-World Example

Imagine a library system that uses a REST API:

- **GET /books**: Retrieves a list of all books.
- **GET /books/10**: Retrieves details of a book with ID 10.
- **POST /books**: Adds a new book to the library.
- **PUT /books/10**: Updates the book with ID 10.
- **DELETE /books/10**: Deletes the book with ID 10.

### REST vs SOAP

While REST is simple and uses HTTP, SOAP (Simple Object Access Protocol) is a more complex system with strict standards. SOAP is good for services requiring high security, but REST is easier to use and is preferred for most web and mobile applications.

### References

* [REST Architecture Explained - YouTube](https://www.youtube.com/watch?v=k2AR9hINWLs&t=151s)
* [HTTP Methods Explained - TheServerSide](https://www.theserverside.com/blog/Coffee-Talk-Java-News-Stories-and-Opinions/HTTP-methods)
* [Advantages and Disadvantages of REST API - Krify](https://krify.co/advantages-and-disadvantages-of-rest-api/)
* [SOAP vs REST - AWS Comparison](https://aws.amazon.com/compare/the-difference-between-soap-rest/)

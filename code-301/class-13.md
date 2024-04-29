Which HTTP method would you use to update a record through an API?
PUT or PATCH.
Which REST methods require an ID parameter?
GET, PUT, PATCH, and DELETE.

What’s the relationship between REST and CRUD?
CRUD (Create, Read, Update, Delete) represents the basic operations performed on data in a database. REST (Representational State Transfer) is an architectural style for designing networked applications. In a RESTful API, CRUD operations are typically mapped to HTTP methods: Create (POST), Read (GET), Update (PUT/PATCH), and Delete (DELETE).

If you had to describe the process of creating a RESTful API in 5 steps, what would they be?
- Define Resources: Identify the data entities (resources) your API will expose, such as users, products, or orders.
- Design URIs: Determine the URI structure for accessing each resource. Use meaningful and hierarchical paths, following RESTful principles.
- Choose HTTP Methods: Assign appropriate HTTP methods (GET, POST, PUT, PATCH, DELETE) to each URI based on the desired CRUD operations.
- Implement Handlers: Write code to handle incoming requests to your API endpoints. This involves implementing logic for processing requests, interacting with a database, and generating responses.
- Test and Document: Test your API endpoints to ensure they behave as expected. - Document the API, including URI patterns, supported HTTP methods, request/response formats, and any authentication/authorization mechanisms.
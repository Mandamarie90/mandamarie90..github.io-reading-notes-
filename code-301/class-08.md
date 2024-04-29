#### What does REST stand for?

Representational State Transfer.

#### REST APIs are designed around a ____.

Resource.

#### What is an identifier of a resource? Give an example.

An identifier of a resource is a URI (Uniform Resource Identifier). Example: /users/123.

#### What are the most common HTTP verbs?

GET, POST, PUT, DELETE.

#### What should the URIs be based on?

URIs should be based on resources, not actions.

#### Give an example of a good URI.

/products/123 (for retrieving product with ID 123).

#### What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

A 'chatty' web API makes multiple small requests instead of one larger request, often leading to decreased performance. 

#### What status code does a successful GET request return?

200 OK.

#### What status code does an unsuccessful GET request return?

404 Not Found (if the resource does not exist), or 400 Bad Request (if the request is malformed).

#### What status code does a successful POST request return?

201 Created.

#### What status code does a successful DELETE request return?

204 No Content.
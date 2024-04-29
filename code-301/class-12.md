#### In your own words, describe what each group of status code represents:

- **100's**: Informational codes, server acknowledges the request.
- **200's**: Success codes, server successfully processed the request.
- **300's**: Redirection codes, client needs to take additional action to complete the request.
- **400's**: Client error codes, server couldn't process the request due to client-side issues.
- **500's**: Server error codes, server couldn't fulfill the request due to issues on its end.
#### What is a status code 202?
HTTP status code 202 means "Accepted." It's used when the server has received the request, understood it, and has started processing it, but the processing isn't complete yet. This is often used for asynchronous operations where the server needs more time to finish the requested task. Clients receiving this code should not assume that the request was immediately successful and may need to check back later for updates.
#### What is a status code 308?
HTTP status code 308 means "Permanent Redirect." It tells the client that the requested resource has been permanently moved to a different URL. The client should make future requests to this new URL instead. This status code is similar to 301 (Moved Permanently), but it keeps the original HTTP method of the request unchanged.

#### What code would you use if an update didn’t return data to a client?
If an update operation was performed successfully but didn't return any data to the client, you would typically use HTTP status code 204, which means "No Content." This status code indicates that the server successfully processed the request, but there is no content to send back in the response body. It's commonly used for operations like updating or deleting resources where the client doesn't need to receive any data in response.

#### What code would you use if a resource used to exist but no longer does?
If a resource used to exist but no longer does, you would use HTTP status code 410, which means "Gone." This status code indicates that the requested resource is no longer available on the server and that there is no forwarding address. It differs from 404 (Not Found) in that it explicitly indicates that the resource was once present but has been intentionally removed and is not expected to be available again.

#### What is the ‘Forbidden’ status code?
The "Forbidden" status code is HTTP status code 403. It means that the server understood the request from the client, but the server is refusing to fulfill it. Essentially, it indicates that the client does not have permission to access the requested resource.

#### Why do we need to pull our MongoDB database string out of our server and put it into our .env?
Putting the MongoDB database string into a `.env` file is a security measure. It protects sensitive information like passwords and URLs by keeping them separate from the main code. This separation also makes it easier to manage configurations for different environments like development and production.

#### What is middleware?
Middleware is a tool used in software that sits between different parts of an application. It handles tasks like authentication, logging, and data processing before requests are handled by the main part of the application. Similarly, it can modify or process responses before they're sent back to the user. Essentially, middleware helps manage and enhance how requests and responses are handled in an application.

#### What does app.use(express.json()) do?
`app.use(express.json())` tells your Express application to automatically parse incoming requests with JSON payloads. This means it can read JSON data sent by clients and makes it available in `req.body` for easy access in your routes and handlers.

#### What does the /:id mean in a route?

In a route, /:id represents a route parameter in Express. It captures a part of the URL path and makes it accessible in the route handler through req.params.id.

#### What is the difference between PUT and PATCH?

PUT is used to completely replace a resource with the new data provided in the request. PATCH is used to make partial updates to a resource by sending only the changes.
#### How do you make a default value in a schema?

To set a default value for a field in a schema, you can use the default property when defining the schema field. 

#### What does a 500 error status code mean?
A 500 error means something went wrong on the server's side while handling the request. It's like saying, "Oops, the server messed up."

#### What is the difference between a status 200 and a status 201?
Status code 200 (OK): It means everything went fine, and the server responded with the requested information.

Status code 201 (Created): It means the server successfully created a new resource based on the request sent by the client.
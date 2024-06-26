#### Classes are a template for creating ____. 

Objects

#### Can a class declaration be hoisted?

No

#### How would you describe a constructor and contextual “this” to a non-technical friend?

A constructor is like a recipe in a cookbook. It's used to create new instances, or copies, of something. 

The "this" keyword is like saying "this one" or "this thing" in a conversation. It helps us refer to specific parts of the thing we're talking about.

#### Within Express, what does routing refer to?

Routing in Express refers to directing incoming requests to specific endpoints (URLs) in the application based on the request method and URL.

#### What is the difference between a route path and a route method?

A route path in Express is the URL pattern that the server listens for and matches incoming requests against. A route method, on the other hand, is the HTTP method (such as GET, POST, PUT, DELETE) used to handle the request matched by the route path.

#### When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?

It's appropriate to add `next` as a parameter to a route handler or middleware in Express when you want to pass control to the next middleware function in the stack. If `next` has been passed to your middleware, you must call it within your middleware function to pass control to the next middleware in the stack.

#### What is an Express Router?

An Express Router is a middleware that allows you to group related routes together, making your code more organized and modular. It helps in organizing routes for specific parts of your application.

#### By what mean do we initialize express.Router() in an express server?

We initialize `express.Router()` by calling it as a function, and then assigning it to a variable. For example: `const router = express.Router();`

#### What do we use route middleware for?

We use route middleware in Express to perform tasks such as authentication, input validation, logging, or any other processing before or after handling a request for a specific route.

#### learning goals

After reading and reviewing the class README, my learning goals are:

1. Understand the concept of using separate routers with Express.router() to organize route handling logic in an Express server.
2. Gain proficiency in building a REST API server using Express.
3. Learn to use Sequelize models and schemas to perform CRUD operations in a SQL database.
4. Understand how to respond to request queries and parameters in routes.
5. Learn how to test code that relies on a Postgres database server.
6. Familiarize myself with route modules and route prefixes to enhance code organization.
7. Gain proficiency in utilizing Sequelize for database initialization and performing basic SQL operations.
8. Understand how to connect to a hosted Postgres database in the cloud for deployment.

By achieving these learning goals, I aim to enhance my skills in building robust and scalable web applications using Express and Sequelize.
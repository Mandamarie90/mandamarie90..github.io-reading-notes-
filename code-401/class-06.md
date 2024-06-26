### Safely Hashing and Storing Passwords

#### Explain to a non-technical friend how you would safely hash and store a password.

To safely hash and store a password, I'd use a cryptographic hashing algorithm like SHA-256 or bcrypt. First, I'd hash the password using the chosen algorithm, then store the hashed password in a secure database.

### Bcrypt

#### What is Bcrypt?

Bcrypt is a password-hashing function designed to be slow and computationally intensive, making it resistant to brute-force attacks.

#### Why might you use something like Bcrypt?

Bcrypt is used to securely hash passwords because of its resistance to brute-force attacks and its ability to adjust its computational cost over time, making it adaptable to increasing computing power.

### Basic Authentication

#### What is Basic Authentication?

Basic Authentication is a simple authentication scheme built into the HTTP protocol, where the username and password are sent as Base64 encoded strings in the request header.

#### What properties are necessary in the header of a Basic Auth request?

The Basic Auth header requires the "Authorization" property, which includes the word "Basic" followed by a space and the Base64 encoded string of "username:password".

#### How are username:password in Basic Auth encoded?

In Basic Authentication, the "username:password" combination is encoded using Base64 encoding before being sent over the network.

### Authentication Process

#### Define the authentication process to a non-technical recruiter.

In the authentication process, users provide their credentials (such as username and password), which are then verified against stored credentials in a secure manner. Successful authentication grants access to the system or resource.

#### How should your error messaging respond (both HTTP and HTML)? Why?

For HTTP responses, error messages should have appropriate status codes (e.g., 401 for unauthorized access) and clear, user-friendly HTML content to guide users in resolving authentication issues. Clear error messages help users understand what went wrong and how to rectify it.

### OWASP Auth Cheatsheet

#### Consider OWASP fundamentals any time you interact with authentication. Why?

Applications developed with security in mind from the start are less vulnerable to attacks throughout their lifecycle.


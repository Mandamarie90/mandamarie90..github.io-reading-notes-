### Explain the difference between a query string parameter and a path parameter.
A path parameter is part of the main URL and points to a specific thing, like a product or page ID. Query string parameters are added at the end with a `?` and are used for sorting or filtering stuff.

### What would our API URL with a path id parameter be given the following information:
Your API URL would look like this: `http://our-site.com/v3/stuff/things`

### We have created a dynamic API with an “interface”. Describe how that interface works to a non-technical friend.
Think of our API's interface like a remote control for our website. It has buttons (commands) that let other programs ask for data or tell our site what to do, just like changing channels or adjusting the volume.

### Review Auth Server Build
To give feedback on the Auth Server Build, I'd need more details about what it does and how it's set up. Generally, I'd look at how it handles security for user logins and how well it integrates with other parts of the system.

### Describe how you would use middleware to implement basic and bearer auth.
 Middleware acts like a bouncer. For basic auth, it checks if the username and password provided in the web header are correct. For bearer auth, it checks if the access token you provide is valid before letting you in.

### Describe the handshake necessary to implement OAuth.
 Implementing OAuth is like getting a VIP pass to a concert. First, you request access, get a special ticket (authorization grant) if approved, exchange that ticket for a VIP pass (access token), and then use that pass to get into the concert (access resources).

### Describe how Role Based Access Control works to a non-technical friend.
It's like having different keys for different rooms based on who you are in a building. RBAC gives you keys (access) to certain areas (parts of a system) depending on your role, like a manager or a staff member.
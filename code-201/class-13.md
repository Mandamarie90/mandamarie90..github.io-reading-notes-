### Local storage

#### Why would a developer use local storage for a web application?

A developer might use local storage for a web application to store data persistently on the user's device, enabling offline capabilities, improving performance, and enhancing the user experience through personalized settings and preferences.

#### What information should not be stored in local storage?

Sensitive information such as passwords, authentication tokens, or any other personally identifiable information (PII) should not be stored in local storage. This is because local storage is not as secure as server-side storage and can be accessed and manipulated by the user or other scripts running in the browser. Storing sensitive information in local storage increases the risk of data breaches and security vulnerabilities. Instead, sensitive data should be stored securely on the server and transmitted over secure channels when needed.

#### Local storage can store what type of data? How would you convert it to that type before storing?

Local storage can store data as strings. To store data of other types such as objects or arrays, you need to convert them to strings before storing them using methods like JSON.stringify(). When retrieving data from local storage, you can convert the stored string back to its original type using methods like JSON.parse().

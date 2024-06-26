### What is a Web Socket?

A Web Socket is a communication protocol that provides full-duplex communication channels over a single TCP connection.

### Describe the Web Socket request/response handshake and what happens once the connection is established.

The Web Socket handshake starts with an HTTP request from the client to the server, which then responds with an HTTP 101 status code, indicating the protocol switch. Once established, the connection allows for bidirectional, real-time communication.

### Web Sockets provide a standardized way for the server to send content to a client without first receiving a ____ from that client.

Request

### What does the event handler io.on() do?

The event handler `io.on()` listens for events of a specified type and executes a callback function when such an event occurs.

### Describe some possible proof of life or proof that the code works as expected.

Possible proofs include seeing expected log messages in the console, receiving expected responses from the server, and successful real-time updates in the client application.

### What does socket.emit() do?

The `socket.emit()` method sends an event with optional data to the server or to clients.

### What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).

WebSocket is a protocol for real-time communication, while Socket.IO is a library that provides additional features like reconnection, event handling, and broadcasting, built on top of WebSockets.

### When would you use Socket.IO?

Use Socket.IO when you need real-time communication along with additional features like automatic reconnection, room support, and broadcasting.

### When would you use WebSockets?

Use WebSockets when you need a simple, low-latency, bidirectional communication channel without the need for additional features provided by Socket.IO.

### What are a couple of key takeaways from this video?

The Network Layer handles IP addressing and routing.
The Data Link Layer deals with MAC addressing, framing, and error detection.

### Translate the gist of this video to a non-technical friend

Imagine you're about to talk on the phone:

1. **You call** and ask, "Ready to talk?"
2. **They reply**, "Yes, are you?"
3. **You confirm**, "Yes!"

This quick check ensures both of you are ready to chat, just like how computers set up a connection before sharing data. 

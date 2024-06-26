**What is a JSON Web Token (JWT)?**
JWT is a compact, URL-safe means of representing claims to be transferred between two parties. The claims in a JWT are encoded as a JSON object that is used primarily for authentication and information exchange.

**When should we use JSON Web Tokens?**
JSON Web Tokens are ideal for scenarios where authorization and information exchange are needed across different systems, especially in web applications and APIs, due to their ability to carry embedded user or system data securely.

**Claims are expected in which structural component of a JWT?**
Claims are contained in the payload component of a JWT.

**Are JWTs Secure?**
JWTs are secure as long as they are properly implemented with strong encryption algorithms and key management practices. They are designed to ensure that the data they carry cannot be altered without detection.

**If I get a JWT and I can decode the payload, how can we call that secure?**
Decoding the payload of a JWT does not compromise its security because the payload is only base64 encoded, not encrypted. Security comes from the verification of the signature, ensuring that the token has not been tampered with.

**If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.**
Both the sender and receiver must know the secret or have access to the public/private key pair used to create and verify the JWT's signature.

**Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.**
Think of it like sending a sealed envelope through the mail. The contents inside the envelope (the concatenated content) are packaged with a unique seal (the secret). Only the sender knows how to properly seal it, and only the intended receiver can verify the seal and open it securely.

**Why use JWT?**
JWTs are used because they are compact and self-contained, making them efficient for scenarios where bandwidth and performance are critical, such as in web and mobile environments.

**JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.**
Imagine you have a VIP pass for a festival that contains all your access permissions and identification details in a single card that you carry around your neck. Similarly, JWTs carry all the necessary information in one small package, making it easier and faster to use across different services without repeated checks.

**What are the three components (the structure) of a JWT signature?**
A JWT consists of three parts: the header, the payload, and the signature. The header specifies the token type and the encryption algorithm. The payload contains the claims. The signature is used to verify the token's authenticity and ensure it hasn't been altered.
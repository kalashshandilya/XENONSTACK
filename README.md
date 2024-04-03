# **KALASH SHANDILYA**                                                                                       
# **Registration Number : 12015889**













# DEPLOYED LINK:https://classy-quokka-0040a4.netlify.app/


# **Libraries used in the project:**


## **JWT:** 

JWT stands for JSON Web Token. It is a compact and self-contained means of transmitting information between two parties as a JSON object. JWTs are commonly used for authentication and authorization purposes in web applications.

A JWT consists of three parts: a header, a payload, and a signature.

Header: The header typically consists of two parts: the token type, which is JWT, and the hashing algorithm used to create the signature, such as HMAC SHA256 or RSA. It is Base64Url encoded.

Payload: The payload contains the claims or statements about the user or other data being transmitted. The claims can include information like the user's identity, expiration time of the token, and other custom data. It is also Base64Url encoded.

Signature: The signature is generated by combining the encoded header, encoded payload, a secret key (known only to the server), and applying the specified hashing algorithm. The signature ensures the integrity of the token and allows the recipient to verify its authenticity.

To use JWT for authentication, the following process typically occurs:

User Authentication: The user provides their credentials (e.g., username and password) to the server.

Token Generation: Upon successful authentication, the server generates a JWT containing the necessary user information and signs it with a secret key.


## **Bcrypt.js:** 

bcrypt.js is a JavaScript library used for hashing passwords. It provides a secure and efficient way to store user passwords by applying a one-way hashing algorithm with salt. The bcrypt.js library is based on the bcrypt algorithm, which is known for its resistance against brute-force attacks.

## **Sass:** 

Sass stands for Syntactically Awesome Stylesheet
Sass is an extension to CSS
Sass is a CSS pre-processor
Sass is completely compatible with all versions of CSS
Sass reduces repetition of CSS and therefore saves time

## **React-router DOM:** 

React Router DOM is a popular library used for routing in React applications. It provides a declarative way to handle navigation and URL routing within a React application.

React Router DOM is specifically designed for web applications and is built on top of React Router. It extends the core functionality of React Router and adds additional features specifically for browser-based routing.

## **Description:** 

Brief description about the contact APP:

Frontend (React):

The frontend of the app is built using React, providing a user-friendly interface for managing contacts.
Users can sign up and log in to their accounts using username and password credentials.
Upon successful login, users are issued a JSON Web Token (JWT) that authenticates their subsequent requests to the server and the token is stored in the browsers local Storage.
The UI communicates with the backend server to perform CRUD (Create, Read, Update, Delete) operations on contacts.

Backend (Node.js with Express):

The backend is built using Node.js with Express, acting as the server-side component of the application.
MongoDB is used as the database to store contact information securely.
When a user registers, their password is hashed using bcrypt, a password hashing library, and stored in the database.
For user authentication, the backend verifies the user's login credentials and generates a JWT upon successful authentication.
The backend includes endpoints for handling contact-related operations, such as adding new contacts, updating existing contacts, and deleting contacts.
These endpoints are protected using middleware that verifies the JWT included in the request headers to ensure authenticated access.

## **Website images:** 




![image](https://github.com/kalashshandilya/XENONSTACK/assets/81811583/bf145286-a7d1-439a-ac05-7cb17b6f9ebf)





![image](https://github.com/kalashshandilya/XENONSTACK/assets/81811583/ddf23039-e746-4b2c-9fe6-ea19bf44703a)








![image](https://github.com/kalashshandilya/XENONSTACK/assets/81811583/f88c0d51-c0d0-421a-9875-2725fb4d1b95)








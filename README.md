# AUTHENTICATION MECHANISM 
**Authentication** is the process of verifying the identity of a user, system, or entity before granting access to resources or services. It ensures that the entity requesting access is who it claims to be.

## why this repository?
This repository aims to provide comprehensive documentation of various authentication mechanisms used across different systems. It will serve as a reference guide, detailing the different forms of authentication available, their implementations, and potential security vulnerabilities associated with each.

The goal is to not only document authentication methods but also to highlight potential weaknesses, offering insights into areas for improvement in securing applications and services.

# List of Authentication Methods

| **Authentication Method**             | **Description**                                                                 | **Common Usage**                         |
|---------------------------------------|---------------------------------------------------------------------------------|------------------------------------------|
| **Basic Authentication**              | Uses a username and password sent in the request header (base64-encoded).        | Simple API authentication (not secure over HTTP). |
| **Bearer Token Authentication (OAuth 2.0)** | Involves a bearer token passed in the request header.                           | OAuth 2.0, access tokens in APIs.        |
| **API Key**                           | A unique key sent as part of the request header or query parameters.             | Public APIs, key-based services.         |
| **OAuth 2.0 (Authorization Code)**    | A code exchange process where a user authorizes an application to access their data. | Third-party apps, user authentication.  |
| **OAuth 2.0 (Client Credentials Flow)**| Client credentials (client ID and secret) used to authenticate an app.          | Machine-to-machine communication.       |
| **JWT (JSON Web Token)**              | Self-contained token containing claims and metadata.                             | Modern web applications, single sign-on. |
| **HMAC (Hash-based Message Authentication Code)** | Uses a shared secret key to ensure the integrity and authenticity of the message. | Secure APIs, financial systems.          |
| **Digest Authentication**            | A hashed version of basic authentication, more secure.                          | Older systems, where password hashing is required. |
| **Session Cookies**                   | Server issues a session token, used for maintaining authentication across requests. | Web applications.                       |
| **LDAP Authentication**               | Integrates with LDAP directories (e.g., Active Directory) for user authentication. | Enterprise systems, internal services.   |
| **Custom Authentication**             | A combination of various techniques such as API keys, timestamps, and signatures. | Custom applications with unique needs.   |
| **Two-Factor Authentication (2FA)**   | Combines something the user knows (password) with something the user has (token, SMS). | Highly secure systems, banking, apps with sensitive data. |
| **Certificate-Based Authentication**  | Uses SSL/TLS certificates to authenticate the client.                           | Secure web applications, internal APIs.  |

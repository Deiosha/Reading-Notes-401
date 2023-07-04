# Reading Questions

1. What is the primary purpose of JSON Web Tokens (JWTs) and how do they work in terms of encoding and decoding data?

- The primary purpose of JSON Web Tokens (JWTs) is to securely transmit information between parties as a compact and self-contained format. They work by encoding data using a specific algorithm and can be decoded by the recipient using a secret key to verify the token's integrity and access the contained information.

2. How does JWT Authentication integrate with Django REST Framework to secure API endpoints, and what are the key components involved in this process?

- JWT Authentication integrates with Django REST Framework by using JWT tokens to secure API endpoints. Key components include the JWT token, Django REST Framework middleware, and authentication classes for validation and enforcement.

3. Why is Django’s built-in runserver not suitable for production environments, and what are some alternative server options that should be considered for deploying a Django application?

- Django's runserver is not suitable for production due to its lack of security, performance optimizations, and scalability. Alternatives like Gunicorn, uWSGI, or Nginx with uWSGI should be considered for deploying a Django app in production.

## Things I want to learn more about

What are the steps involved in configuring and deploying a Django application with an alternative server option?

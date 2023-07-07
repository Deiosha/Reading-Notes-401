# Reading Questions

1. What are the key principles to follow when organizing and configuring Django settings for a project, according to the “Django Settings Best Practices” reading?

- The key principles for organizing and configuring Django settings are to use separate settings modules for different environments, utilize environment variables for sensitive information, and split settings by purpose to maintain a clean and manageable configuration.

2. How does the White Noise library contribute to the efficient serving of static files in a Django application, and what are the steps to integrate it into a project?

- The White Noise library contributes to efficient serving of static files in a Django application by serving them directly from the application without relying on a separate server like Apache or Nginx, reducing the complexity of deployment. To integrate White Noise, you need to install the library, add it to the project's middleware, and configure it to handle static file serving in the Django settings.

3. What is the purpose of Cross-Origin Resource Sharing (CORS) in web applications, and how can it be implemented and configured in a Django project to control access to resources?

- Cross-Origin Resource Sharing (CORS) allows web applications to control access to resources from different origins. In a Django project, CORS can be implemented by installing the django-cors-headers package and configuring it in the project's settings to define which origins are allowed to access the resources through HTTP headers, such as CORS_ORIGIN_WHITELIST or CORS_ALLOW_ALL_ORIGINS.

## Things I want to learn more about

How does the White Noise library handle static file caching and compression in a Django application?

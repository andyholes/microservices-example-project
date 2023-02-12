## First dive into microservices!
After some time developing monolithic applications, I wanted to try a microservices based SBA.<br><br>

This is a simple online shopping application that contains the following services:

- Product Service: For creating and viewing products. Acts as a catalog
- Order Service: For ordering products
- Inventory Service: Checks whether ordered products are in stock or not
- Notification Service: Send notifications if orders are placed successfully

WebClient is used for synchronous communication between the services through HTTP requests.

Service Discovery pattern is implemented using Netflix Eureka.

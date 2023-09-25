# e-commerce-microservices
A simple e-commerce application built using Spring Boot microservices. The application allows users to browse products, add them to their cart, and place orders.

This repository contains a simple e-commerce application built using Spring Boot microservices. The application allows users to browse products, add them to their cart, and place orders.

The application is made up of two microservices:

* **products-microservice:** This microservice manages product information, such as product name, description, price, and inventory.
* **orders-microservice:** This microservice manages orders, such as customer information, shipping address, and order items.

The microservices communicate with each other using REST APIs.

## Getting started

To get started, you will need to install the following:

* Java 11
* Maven
* Docker (optional)

To build and run the application, follow these steps:

1. Clone the repository:


git clone https://github.com/<your-username>/ecom-app.git
```

2. Navigate to the project directory:

```
cd e-commerce-microservices
```

3. Build the microservices:

```
mvn clean install
```

4. Run the microservices:

```
mvn spring-boot:run
```

If you are using Docker, you can build and run the microservices using the following commands:

```
docker-compose build
docker-compose up -d
```

5. API Endpoints

Products Microservice

GET /products: Get a list of all products.
GET /products/{productId}: Get a specific product by ID.
POST /products: Create a new product.
PUT /products/{productId}: Update an existing product.
DELETE /products/{productId}: Delete a product.
Orders Microservice

GET /orders: Get a list of all orders.
GET /orders/{orderId}: Get a specific order by ID.
POST /orders: Place an order.
PUT /orders/{orderId}: Update an existing order.
DELETE /orders/{orderId}: Cancel an order.


## Testing

To test the application, you can use a tool such as Postman to make requests to the microservices' APIs.

## Deployment

You can deploy the microservices to a cloud platform such as AWS or GCP, or you can deploy them locally using a tool such as Docker Compose.

## Contributing

If you would like to contribute to this project, please feel free to submit a pull request.


You can modify the README file to include more information about your project, such as the features that you have implemented or the technologies that you have used. You can also add instructions on how to contribute to the project.

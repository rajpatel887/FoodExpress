# FoodExpress
This Food Delivery Management System simplifies the process of managing restaurants and cafes. It allows customers to easily browse menus, place orders, and pay, either online or with cash
# Food Delivery System

## Project Overview
A web-based Food Delivery System allowing users to browse restaurants, place orders, and track deliveries in real time. The system is built using *Spring Boot* for the backend API and *React* for the frontend interface.

## Features
- *User Authentication*: Secure sign-up, login, and account management.
- *Restaurant Listings*: Browse restaurants, view menus, ratings, and prices.
- *Search & Filters*: Search food items and filter by cuisine, price, and ratings.
- *Order Management*: Add items to the cart, review the order, and proceed to checkout.
- *Real-Time Tracking*: Track the delivery process (e.g., preparing, in transit, delivered).
- *Admin Panel*: Admins can manage restaurants, menu items, and orders.

## Tech Stack
- *Frontend*: React.js, Axios, HTML5, CSS3
- *Backend*: Spring Boot, Java, REST APIs, Spring Security
- *Database*: MySQL / PostgreSQL
- *Authentication*: JWT (JSON Web Token)
- *Deployment*: Docker (optional), Cloud services (AWS/Heroku)

## Installation

### Prerequisites
- Java 11 or higher
- Node.js and npm
- MySQL/PostgreSQL database

### Backend Setup
1. Clone the repository:
   bash
   git clone https://github.com/rajpatel887/FoodExpress.git
   cd food-delivery-system
   
2. Navigate to the backend directory:
   bash
   cd backend
   
3. Build the project:
   bash
   ./mvnw clean install
   
4. Run the Spring Boot application:
   bash
   ./mvnw spring-boot:run
   

### Frontend Setup
1. Navigate to the frontend directory:
   bash
   cd frontend
   
2. Install dependencies:
   bash
   npm install
   
3. Start the React app:
   bash
   npm start
   
4. The frontend will be accessible at http://localhost:3000.

### Database Configuration
1. Create a new database (e.g., food_delivery_db).
2. Update application.properties in the backend with database connection details:
   properties
   spring.datasource.url=jdbc:mysql://localhost:3306/food_delivery_db
   spring.datasource.username=root
   spring.datasource.password=yourpassword
   
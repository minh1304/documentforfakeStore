# FakeStore Ecommerce Website

## Demo Links
- **Live Website**: [FakeStore](https://fake-store-five.vercel.app)
- **Demo Video**: [Watch Demo](https://www.youtube.com/watch?v=1wALZYWvflo)

## Credentials
- **User Account**:
  - Username: `minh.vo`
  - Password: `123456`
  
- **Admin Account**:
  - Username: `minh1`
  - Password: `123456789`

## Overview
FakeStore is a fully functional ecommerce website where users can browse products, add items to the cart, and complete purchases. Admins can manage products, update order statuses, and control inventory.

## Features
### Main Page
- Browse all available products.
- Filter and sort items for easy navigation.

![Main Page]([path-to-your-image](https://drive.google.com/file/d/1901yfAYeOmq4hNeYyu6wdWcin1JXB6Ak/view?usp=sharing))

### User Registration & Login
- New users can register for an account.
- Existing users can log in to access their cart and orders.

![User Registration](path-to-your-image)  
![Login](path-to-your-image)

### Shopping Experience
- **Add Product to Cart (Main Page)**: Users can add products directly from the main page.
  
  ![Add to Cart](path-to-your-image)

- **Add Product to Cart (Detail Page)**: Users can view detailed product information and add items to their cart.
  
  ![Product Detail](path-to-your-image)

- **Order Success**: Users will see a confirmation page after successfully placing an order.
  
  ![Order Success](path-to-your-image)

### Admin Features
#### Order Management
- Admins can view all orders and update the order status.
- Users can mark their orders as complete once they are received.

![Order Management](path-to-your-image)

#### Product Management
- **Add Products**: Admins can add new products to the store.
  
  ![Add Product](path-to-your-image)

- **Update Products**: Admins can update product details such as price, stock, and description.
  
  ![Update Product](path-to-your-image)

## ERD (Entity Relationship Diagram)
The following ERD represents the database structure of the project, showcasing the relationships between users, products, orders, and more.

![ERD Diagram](path-to-your-image)

## Installation Instructions

To run this project locally:

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/fakestore.git
    cd fakestore
    ```

2. Install dependencies for both frontend and backend:
    ```bash
    npm install
    cd backend
    dotnet restore
    ```

3. Run the application:
    ```bash
    cd frontend
    npm run start
    ```

4. Start the backend server:
    ```bash
    cd backend
    dotnet run
    ```

## Technologies Used
- **Frontend**: React, Axios, Tailwind CSS
- **Backend**: ASP.NET Core, Entity Framework Core
- **Database**: SQL Server
- **Authentication**: JWT (JSON Web Token)

## Future Improvements
- Add product reviews and ratings.
- Implement payment gateway integration.
- Improve performance and load times.
  
## License
This project is licensed under the MIT License.

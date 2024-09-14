# FakeStore Ecommerce Website

## Demo Links
- **Live Website**: [FakeStore](https://fake-store-five.vercel.app)
- **Demo Video**: [Watch Demo](https://www.youtube.com/watch?v=1wALZYWvflo)

## Accounts
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
![Main Page](https://drive.google.com/uc?export=view&id=1vu7r-XjUNfjZETr1lCdD2uM4bcjSucy5)
![](https://drive.google.com/uc?export=view&id=1-G_CW7Ved4hCP_xDM3cy1FmoOk7k2zpM)


### User Registration & Login
- New users can register for an account.
- Existing users can log in to access their cart and orders.

![User Registration](https://drive.google.com/uc?export=view&id=1qRLhOupGUR-vbmUgkXN0kHz5a9MFwvF5)
![Login](https://drive.google.com/uc?export=view&id=167awF4bMEsMkK8WGsnfqgJumHrzv70b3)

### Shopping Experience
- **Add Product to Cart (Main Page)**: Users can add products directly from the main page or from detail product information.

![Add to Cart](https://drive.google.com/uc?export=view&id=1umcZe2xdf-Rb5s3zfQ--MLsX17jopIPi)

- **Order Success**: Users will see a confirmation page after successfully placing an order.

![Order Success](https://drive.google.com/uc?export=view&id=1KhMJndZC2WYAwxGC94cTHQ70OfMeS5vk)
![Order Success](https://drive.google.com/uc?export=view&id=12fgyIAFqdjAlOhCdT5EvMfIYAzaEwqJq)


### Admin Features
#### Order Management
- Admins can view all orders and update the order status.

![Order Management](https://drive.google.com/uc?export=view&id=1fC92MbYlezq1x1PgILUxU3Bwo9d4C7MW)
![Order Detail](https://drive.google.com/uc?export=view&id=1zGtBssRTD90oG3vatk5k5KSMZ5bU6TGa)

- Users can mark their orders as complete once they are received.

![Order Status](https://drive.google.com/uc?export=view&id=1mrEsCFvSxaRvHXzmYL_7N5p2bT_h8H__)
![Order Status 2](https://drive.google.com/uc?export=view&id=1yfONy8SWRi7QLYqoCu38FzXjj3lUibIL)
![Order Status 3](https://drive.google.com/uc?export=view&id=1T_wJQtBay2deOdQwlhAqusBlfaY9YJvC)

#### Product Management

- **Update Products**: Admins can update product details such as price, stock, and description.

  ![Update Product](https://drive.google.com/uc?export=view&id=1B-5pCZg177s3t9nIzygpfZZ9d9XitaQZ)
  ![Update Product](https://drive.google.com/uc?export=view&id=11Npn1_QFb26LZZMzp5beJmDEWbUzhBc0)
  ![Update Product](https://drive.google.com/uc?export=view&id=1mTLFgE5oLzRZpSGNHYB7JX6VHPzy_Wfo)


- **Add Products**: Admins can add new products to the store.
  
  ![Add Product](https://drive.google.com/uc?export=view&id=1bmQ0vHG_IQ_oI3hQvnpgQphnrSMEdq9Z)
  ![Add Product](https://drive.google.com/uc?export=view&id=1iP0uGod4Wfrcq7rULSsCL3gQcmSwc3od)

## ERD (Entity Relationship Diagram)
The following ERD represents the database structure of the project, showcasing the relationships between users, products, orders, and more.

![ERD Diagram](https://drive.google.com/uc?export=view&id=1yOeFUEyG21OH1Na4i1v3wtpmh8VZogpQ)

## Technologies Used
- **Frontend**: React, Axios, Tailwind CSS, Redux Toolkit
- **Backend**: ASP.NET Core 7.0, Entity Framework Core
- **Database**: SQL Server
- **Authentication**: JWT (JSON Web Token)

## Source Code
- **Frontend**: [GitHub Repository](https://github.com/minh1304/fakestore)
- **Backend**: [GitHub Repository](https://github.com/minh1304/fakestoreNet)

## Technical Description
- **Backend**: Developed using .NET Core 7.0 with Entity Framework Core for database management (SQL Server). Created RESTful APIs and integrated JWT authentication for secure access. Dependency Injection (DI) was used for modular, flexible management. The backend was containerized and deployed to Azure Container Apps via Docker Hub.
  
- **Frontend**: Built with React and styled using Tailwind CSS. Managed state with Redux Toolkit, and deployed the application to Vercel for seamless, efficient hosting of the single-page application (SPA).


## Future Improvements
- Add product reviews and ratings.
- Implement payment gateway integration.
- Improve performance and load times.


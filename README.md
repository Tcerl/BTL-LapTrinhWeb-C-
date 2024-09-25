# CameraShop - ASP.NET Web Application for Selling Cameras

## Project Overview

CameraShop is a web-based application built with ASP.NET, designed for selling cameras online. The platform allows users to browse various camera products, view detailed information, manage their shopping cart, and place orders. Admin users can manage products, categories, and view sales reports.

## Features

### User Features:
- **Browse Cameras**: View a list of available cameras with options to filter by categories, price range, and brand.
- **Product Details**: View detailed information for each camera, including specifications, images, and customer reviews.
- **Shopping Cart**: Add cameras to the shopping cart and proceed to checkout.
- **Order History**: View past orders and their status.
- **User Authentication**: Register, login, and manage user profiles.
  
### Admin Features:
- **Product Management**: Add, edit, and delete camera products.
- **Category Management**: Create and manage product categories.
- **Order Management**: View and update order statuses.
- **Sales Reports**: View sales data and reports.

## Technologies Used

- **ASP.NET Core MVC**: The core framework for building the web application.
- **Entity Framework Core**: For database access and ORM (Object Relational Mapping).
- **SQL Server**: The database used for storing product, user, and order data.
- **Bootstrap**: For responsive front-end design.
- **jQuery**: To enhance front-end interactivity.
- **Identity**: For user authentication and authorization.

## Project Structure

The project follows the standard ASP.NET MVC architecture:

- **Models**: Contains the data models, such as `Product`, `Category`, `Order`, and `User`.
- **Views**: Razor views for rendering the user interface.
- **Controllers**: Handles the request/response cycle and business logic.

### Key Directories:
- `/Controllers`: Contains the application's controllers like `HomeController`, `ProductController`, `AdminController`.
- `/Views`: Razor view files for the user and admin interfaces.
- `/Models`: Data models representing the application's data entities.
- `/wwwroot`: Contains static files like CSS, JavaScript, and images.

## Setup Instructions

### Prerequisites:
- [.NET SDK](https://dotnet.microsoft.com/download) (ASP.NET Core 6.0 or later)
- [SQL Server](https://www.microsoft.com/en-us/sql-server) or [SQL Server Express](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)

### Steps:
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/CameraShop.git
   cd CameraShop

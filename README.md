# Petals&Pines - Floral E-Commerce Platform



## Overview

Petals&Pines is a modern e-commerce platform designed to revolutionize traditional floral shops by providing a seamless online shopping experience. Our platform connects customers with beautiful floral arrangements while streamlining shop operations through efficient inventory and order management.

## Key Features

### For Customers
- **User Registration & Authentication**: Secure sign-up and login system
- **Product Browsing**: Intuitive search and filtering for plants, bouquets, and arrangements
- **Shopping Cart**: Easy item management before checkout
- **Secure Checkout**: Smooth purchasing process

### For Administrators
- **Product Management**: Full CRUD operations for floral inventory
- **Order Management**: Track and fulfill customer orders
- **User Management**: Admin control over customer accounts

## Technology Stack

### Frontend
- **HTML5**, **CSS3**, **JavaScript** - Core web technologies
- **Express.js** - Web application framework

### Backend
- **Node.js** - JavaScript runtime environment
- **Express.js** - Web application framework

### Database
- **MongoDB** - NoSQL database for flexible data storage

### DevOps
- **Docker** - Containerization for consistent deployments
- **DevSecOps Practices** - Security integrated throughout development lifecycle

## System Architecture

We follow the **MVC (Model-View-Controller) Architecture** pattern:
- **Model**: Manages data logic and database interactions
- **View**: Handles UI representation and user interactions
- **Controller**: Processes requests and manages data flow

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- MongoDB Atlas account or local MongoDB installation
- Docker (for containerized deployment)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/petals-and-pines.git
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Configure environment variables (create a `.env` file):
   ```
   MONGODB_URI=your_mongodb_connection_string
   PORT=3000
   SECRET_KEY=your_secret_key
   ```
4. Start the development server:
   ```bash
   npm start
   ```

## Deployment

For containerized deployment using Docker:
```bash
docker build -t petals-and-pines .
docker run -p 3000:3000 -d petals-and-pines
```

## Contributing

We welcome contributions! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Inspired by TopBloemen.nl, FlowersToUAE, and Utty Flower Shop
- Special thanks to our advisors and mentors

---

**Petals&Pines Team**  
Sagar Lepcha, Kuenga Tshering, Tandin Zangmo

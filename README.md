# Full-Stack Finance App

A comprehensive full-stack finance tracking application with user authentication, transaction management, and data visualization. Built with modern technologies and fully containerized with Docker.

## Features
- User authentication and authorization
- Track income and expenses
- Categorize transactions
- View financial summaries and analytics
- Secure password hashing
- RESTful API architecture
- Fully containerized deployment

## Demo
### User Authentication
<img src="signup.gif" alt="User Signup Demo" width="600"/>

### Transaction Management
<img src="transactions.gif" alt="Transaction Features Demo" width="600"/>

## Tech Stack

**Frontend:**
- React with Vite
- TailwindCSS
- JavaScript

**Backend:**
- Node.js
- Express.js

**Database:**
- PostgreSQL

**DevOps:**
- Docker & Docker Compose
- Nginx (reverse proxy)



## Architecture

This application follows a three-tier architecture:
- **Frontend**: React application served through Nginx
- **Backend**: Express REST API handling business logic
- **Database**: PostgreSQL for data persistence

All services are containerized and orchestrated using Docker Compose.

## Installation & Setup

### Prerequisites
- Docker
- Docker Compose

### Running with Docker (Recommended)

1. Clone the repository:
```
git clone https://github.com/ThirushanPather/full-stack-finance-app.git
cd full-stack-finance-app
```

2. Create a .env file in the root directory

3. Start the application:
```
docker-compose up -d
```

## Database Schema
The application uses two main tables:

users: Stores user account information with hashed passwords
transactions: Records all financial transactions linked to users

See init.sql for the complete schema.

## Project Status
🚧 Currently in development
Future Enhancements

Data visualization with charts
Budget planning features
Export transactions to CSV
Mobile responsive design improvements
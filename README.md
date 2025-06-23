# Airbnb Clone Project

This project is a backend clone of Airbnb, designed to practice building a real-world booking platform.  
The goal is to build a scalable backend using Django, with features like property listings, user management, bookings, and reviews.
## Technology Stack

- **Django:** Web framework used to build the backend APIs.  
- **MySQL/PostgreSQL:** Database system to store users, properties, and bookings.  
- **GraphQL:** (Optional) API query language for efficient data fetching.  
- **Docker:** Containerization tool for consistent development and deployment environments.  
- **GitHub Actions:** Tool to automate testing and deployment pipelines.
## Team Roles

- **Backend Developer:** Responsible for building and maintaining the server-side logic, database models, and API endpoints.
- **Database Administrator:** Designs, manages, and optimizes the database, ensuring data integrity and performance.
- **Frontend Developer:** (If applicable) Works on the user interface and experience, integrating with the backend APIs.
- **DevOps Engineer:** Manages deployment, CI/CD pipelines, and infrastructure to ensure smooth and automated releases.
- **QA Engineer:** Tests the application manually and/or automatically to ensure it works correctly and securely.
## Database Design

The main entities in the database include:

- **Users:** Stores information about users such as username, email, password, and contact details.
- **Properties:** Details about listed properties including title, description, location, price, and availability.
- **Bookings:** Records bookings made by users with start date, end date, total price, and status.
- **Reviews:** Feedback left by users on properties, including rating and comments.
- **Payments:** Information about payment transactions including amount, payment method, and status.

Relationships:
- A user can list multiple properties.
- A booking is linked to one property and one user.
- A user can leave multiple reviews, each linked to a property.
- Payments are linked to bookings.

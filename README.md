# Full Stack Web Application

## Overview
This project is a fully functional full stack web application that serves both customer-facing and administrative purposes. It includes dynamic frontend features, secure admin login authentication, and robust backend functionalities using a NoSQL database. Below, you will find detailed information about the architecture, functionality, testing, and a reflection on the development process.

---

## Architecture

### Frontend Development
This application employs two different frontend approaches:
- **Customer Side**: A Single Page Application (SPA) built with Angular, providing dynamic and seamless interactions without full-page reloads.
- **Admin Side**: Server-rendered pages using Express HTML and JavaScript, ensuring simplicity and reliability for security-focused tasks.

### Backend Development
The backend utilizes a **NoSQL MongoDB database**. MongoDB was chosen for its:
- Flexibility in handling unstructured data such as user details and trip itineraries.
- Schema-less design, which supports rapid development and adaptability.
- Scalability, allowing the application to manage large volumes of user data and operations efficiently.

---

## Functionality

### JSON and Its Role
**JSON (JavaScript Object Notation)** is a lightweight data format used to structure and transmit data between the frontend and backend. While JSON is not a programming language like JavaScript, it seamlessly integrates with JavaScript-based applications. In this project, JSON facilitated:
- Data exchange between the Angular SPA frontend and the Express backend.
- Operations such as user authentication, trip retrieval, and updates.

### Refactoring and Reusable Components
During development, code refactoring was essential to improve functionality and efficiency. Key examples include:
- **Reusable UI Components**: Common elements like forms, modals, and data tables were created as reusable components. These improved consistency and maintainability while reducing redundancy.
- **Global Updates**: Refactored components ensured that updates applied globally, streamlining future maintenance.

---

## Testing

API testing ensured the application’s reliability and security, especially for secure admin authentication. Key testing methods included:
- **Unit Testing**: Tested individual API endpoints for proper data handling.
- **Integration Testing**: Verified interactions between the frontend and backend components.
- **Postman Testing**: Simulated requests to secured endpoints to test authentication protocols, such as token-based access.

Key concepts for testing:
- **Methods**: Tested CRUD operations (`GET`, `POST`, `PUT`, `DELETE`) for various endpoints.
- **Endpoints**: Ensured data consistency and integrity for routes such as user authentication and trip management.
- **Security**: Verified that protected routes rejected unauthorized requests while maintaining smooth access for authenticated users.

---

## Reflection

This project has significantly contributed to my professional growth and skill development in full stack web application development. Through this course, I have:
- Gained expertise in integrating frontend and backend technologies, including Angular, Express, and MongoDB.
- Mastered secure login authentication and API testing techniques.
- Improved my problem-solving abilities through code refactoring and performance optimization.

These skills have prepared me for real-world challenges in the software development field, making me a more marketable candidate in my career.

---

## Project Setup

### Prerequisites
- Node.js and npm
- MongoDB
- Angular CLI

### Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>

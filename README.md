# Contact Management System

Smart Contact Manager is a full-stack Spring Boot web application that helps users manage personal or business contacts efficiently. It includes secure authentication, email integration, file uploads, and export functionality.

## Features

- **User Authentication**
  - Signup/Login with Email verification
  - OAuth Login with Google and GitHub
- **Contact Management**
  - Create, update, delete, and search contacts
  - Upload and manage profile pictures (Cloudinary)
- **Email Integration**
  - Send emails with attachments via JavaMail API
- **Export & Reports**
  - Export contact data to PDF and Excel
- **User Experience**
  - Dark/light mode support
  - Pagination and contact favorites
- **Security**
  - Role-based access with Spring Security
- **Performance**
  - Optimized with Spring Data JPA

## Tech Stack

- **Backend:** Spring Boot, Spring MVC, Spring Security, Spring Data JPA
- **Frontend:** Thymeleaf, JavaScript
- **Database:** MySQL
- **Others:** JavaMail API, Cloudinary SDK, OAuth 2.0

## Getting Started

1. Clone the repository  
   `git clone https://github.com/yourusername/contact-management-system.git`

2. Configure `application.properties` with your database and Cloudinary credentials.

3. Run the application  
   `./mvnw spring-boot:run` or from your IDE.

4. Open in browser  
   `http://localhost:8080`

## Screenshots

(Add screenshots or GIFs here to showcase the UI)

## License

This project is open source and available under the [MIT License](LICENSE).

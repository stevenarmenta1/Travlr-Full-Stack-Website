# Travlr-Full-Stack-Website

## Overview
Travlr is a fullstacvk website built to serve customers and admin users. This application allows users to explore and book travel adventures while also providing admins with secure tools to manage tour packages. The final iteration includes a secure admin login system with authentication features for enhanced security.

---

## Architecture
The frontend of the Travlr application has been shaped in multiple iterations. Initially the project was built with a static HTML and JavaScript files rendered using Express allowed us to quickly build and serve basic views. As the project grew the application transitioned into using a single-page application (SPA) architecture to offer a more dynamic and interactive user experience without requiring full page reloads. This final iteration to SPA allowed for a better user interface and performance optimization.

On the backend, we used a NoSQL MongoDB database. MongoDB was the best solution for this project due to its flexibility with document-based data, ease of scaling, and compatibility with JSON data formats. MongoDB allowed the application to quickly iterate through design changes without being restricted by rigid schemas, which was especially helpful during the development of dynamic tour data.

---

## Functionality

JSON short for JavaScript Object Notation differs from JavaScript in that it is a lightweight data format used for storing and transporting data. It's not executable code like JavaScript, but rather a structured way to represent data. JSON plays a crucial role in connecting the frontend and backend because the frontend sends requests and receives responses in JSON format allowing both layers of the application to communicate efficiently.

Throughout development, I refactored components to enhance maintainability and readability. For instance, I converted several static HTML templates into reusable UI components such as navigation bars, the tour cards, and form inputs. This reduced code duplication and made updates easier across the application. Reusable components also enhanced consistency in the user interface and streamlined future iterations.

---

## Testing

Understanding how different HTTP methods (GET, POST, PUT, DELETE) correspond to various endpoints was key in developing and testing the API. I used tools like Postman to manually test endpoints and ensure correct data flow throughout the application. As authentication was added, particularly for the admin login, testing required managing sessions and tokens, which introduced complexity. I learned to handle protected routes and verify security measures such as password hashing and session handling, ensuring that only authorized users could access administrative functions.

---

## Reflection

This Full stack course has tremendously helped me progress toward my professional goals by providing hands-on experience with building a complete full stack application. I have gained proficiency in working with a MEAN Stack: Node.js, Express, MongoDB, Angular and frontend technologies like JavaScript and templating engines. More importantly, I learned how to connect these pieces into a cohesive product, from database to frontend to user authentication.

The most valuable skills I’ve gained include developing RESTful APIs, managing data flow between client and server, implementing secure login features, and writing clean, reusable code. These experiences have made me a more confident and marketable full stack developer, ready to take on real-world projects and continue growing in the field.

---

## Repository

GitHub: [Travlr Full Stack Website](https://github.com/stevenarmenta1/Travlr-Full-Stack-Website)

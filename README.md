# Overview #
This project aims to create ‘ConnectHub’, a social networking website where users with similar interests can connect and collaborate. Using a client-server setup, users interact with a website to access features like messaging, interest-based groups, events, job listings, and resource centers. We will test the system using POSTMAN, a tool for efficient API testing, ensuring everything works correctly. Detailed responses will be analyzed to guarantee proper functionality, and automation features will be used to create tests that can be repeated. Additionally, we will test the website's performance under different loads to see how well it handles high traffic. Overall, this project aims to promote community engagement as every other platform and collaboration among users with various interests and backgrounds.

# System Design # 
ConnectHub uses a client-server setup. Users interact with a web-based front end, while a backend server manages data processing, storage, and business logic.

### Front End ###
-	The front end of the platform is created using contemporary web technologies like Sass (short for syntactically awesome style sheets) a dynamic style sheet language that extends CSS, along with JavaScript.
-	It offers an intuitive user interface enabling seamless navigation across platform sections, content interaction, and profile management. 
-	This interface adapts responsively, ensuring smooth functionality across a spectrum of devices, encompassing desktops, tablets, and smartphones.

### Backend
-	The backend is constructed using a microservices structure, enabling scalability, adaptability, and maintainability. 
-	It is composed of multiple standalone services, each handling different tasks on the platform. 
-	These backend services are created using Node.js and interact with one another through RESTful APIs. 
-	We might implement JWT (JSON Web Tokens) for secure authentication and authorization.


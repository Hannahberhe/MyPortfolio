# Project #1

## Description & Purpose:
This application is a journal platform where users can create and manage their notes. This program was created to provide a simple, efficient, and secure way for users to record, update and retrieve their personal notes. This would help users keep track of their thoughts, ideas, or important reminders.
Overall Structure & Design Process: The application is a Node.js Express application with an SQLite database. The database schema includes a model for journal entries with titles and notes as properties. Before building, a design process was followed, involving identifying key functionalities, creating a database schema, and defining required routes and responses. Also, considerations were made on user authentication and app security, for which Auth0 and OpenID Connect was chosen.
Code Explanation: The application is divided into separate modules, each handling a specific task, such as server setup, database connection, route definition, and data seeding. Auth0 was used for user authentication, Sequelize ORM was used for database operations, and dot env was used for environment variable configuration. The main server file sets up the Express server and the required routes. For populating the database with initial data, a separate file was created for seeding data.
 Final Application & Functionality: The final application provides an endpoint for accessing and managing notes. Users can view, add, and manage their personal notes through the application. Authentication is required to ensure secure access. An additional route /adas_journal is provided for future enhancement.

## Technologies:

  Node.js & Express: for server setup and defining routes.
  Sequelize & SQLite: for database operations and storage.
  Auth0 & OpenID Connect: for user authentication.
  dotenv: for configuring environment variables.

## Link to the project : 
	https://github.com/OperationAda/AdasJournal-1

## Competencies

# JOB FUNCTION 2:3 Can develop effective user interfaces				
As part of my project, I had to conceptualize a secure and user-friendly journal application. It required a deep understanding of user requirements and translating those into a simple yet efficient application.
## JF 2.4: Can create simple software designs to effectively communicate understanding of the program				
My goal was to create a software design that effectively communicates the journal application's structure. I made the application blueprint using software design tools, including the server setup, database connections, routes, and data seeding operations. This approach helped me map out the application's various components, enhancing the system's overall understanding.
## JF 2.6: Can translate wireframes into User Interfaces				
Though this project was mostly back-end focused, I still had to visualize how the endpoints would interact with potential front-end interfaces. I created mockups of how the endpoints might be used in a user interface, such as forms for creating and editing journal entries and list views for displaying them. This allowed me to design the API with the final user interface in mind.

## Describe a situation where you demonstrated this job function:
The current application could not handle user authentication or route organization effectively. I had to improve these aspects to create a secure and efficient application. I started by analyzing the problem, gathering user feedback, and researching the best authentication and route management practices.

## Summarize the actions you took to accomplish the goal:
I implemented an OpenID Connect authentication system using Auth0, which provided a secure login system. I created separate route handlers for each endpoint for route organization, improving the application's structure and maintainability. The high-level application structure was represented as wireframes to create a blueprint for the project.

## Emphasize the results of this action for your team or your learning:
The new authentication system now provides secure access to the application. The route organization has made the application more manageable and scalable. The experience has honed my skills in analyzing user problems, creating effective software designs, and translating these designs into a working application.

### JOB FUNCTION 4:
I managed and deployed the journal application, conducted testing, and ensured that it adhered to industry security standards.
### JF 4.3: 
Leveraging Node.js capabilities, I successfully managed and deployed the code into the development environment. I provided a secure and reliable user experience by enforcing secure practices and standards.

## Describe a situation where you demonstrated this job function:
I was responsible for deploying the journal application, ensuring it was secure and functional in the live environment.

### Summarize the actions you took to accomplish the goal:
To accomplish this, I first audited the application for any potential security risks, implementing necessary protection measures. I then tested the application thoroughly in a local environment before deploying it. Upon ensuring everything worked as expected, I deployed the application on a server.

### Emphasize the results of this action for your team or your learning:
As a result, the application was successfully deployed and securely available for use. This process has reinforced my skills in managing and deploying applications, conducting thorough testing, and adhering to industry security standards.




Inventory Management System (JavaFX)
A high-performance desktop solution for inventory lifecycle management, designed with a focus on data integrity, relational consistency, and user-centric design. This application provides a scalable framework for managing the complex relationships between component parts and finished products.

🚀 Core Functionalities
Full CRUD Lifecycle: Seamless Create, Read, Update, and Delete operations for both individual parts and composite products.

Advanced Data Validation: Sophisticated business logic prevents data corruption, such as blocking the deletion of products currently associated with active parts.

Real-Time Dynamic Search: Instant, non-blocking filtering by ID or name to navigate large datasets efficiently.

Relational Object Mapping: Supports complex entities by managing "Parts" as standalone items and "Products" as composite entities.

Robust Exception Handling: Custom alerts and input validation (utilizing Regular Expressions) to ensure data cleanliness before database commits.

🏗️ Technical Architecture
The application is built using the Model-View-Controller (MVC) architectural pattern to ensure a strict separation of concerns, facilitating easier maintenance and future scalability.

Model: Centralized data management within an Inventory hub for optimized data flow.

View: Responsive UI layouts designed with FXML for a modern desktop experience.

Controller: Dedicated logic handlers for UI interaction, data validation, and database communication.

🛠️ Tech Stack
Language: Java 11+

GUI Framework: JavaFX (FXML)

Database: MySQL

Build Tools: Maven & IntelliJ IDEA

⚙️ Installation & Deployment
Clone the Repository:

Bash
git clone https://github.com/HughMorris01/Inventory_Management_Sys.git
Database Configuration: Ensure a MySQL instance is running and update the connection strings within the source code to match your environment.

Environment Setup: Verify the JavaFX SDK is correctly configured in your library settings.

Run Application: Open the project in IntelliJ IDEA and execute the Main class.

Technical Documentation: Detailed Javadoc is included in the /Javadoc directory, providing full technical specifications for all classes and methods.

Would you like me to draft a "Future Roadmap" section that outlines how this system could be expanded with features like user authentication or cloud database integration?

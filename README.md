Inventory Management System (JavaFX)
A robust desktop application designed to manage complex inventories of parts and products. This system allows for full lifecycle management of inventory items while implementing specific business logic to ensure data integrity and relational consistency.

🛠 Features
Complete CRUD Operations: Create, Read, Update, and Delete functionality for both Parts and Products.

Logical Validation: Implements business rules to prevent the deletion of products that are currently associated with one or more parts.

Dynamic Search: Real-time filtering for inventory items by ID or Name.

Relational Data Management: Supports "Parts" as standalone entities and "Products" as composite entities that can consist of multiple parts.

Error Handling: Custom exception handling and user alerts for invalid data entry or logical errors.

🚀 Tech Stack
Language: Java 11+

GUI Framework: JavaFX (FXML)

Database: MySQL

IDE/Build Tools: IntelliJ IDEA / Maven

📁 Project Structure
src/: Contains the Java source files, including controllers for the UI and the data model classes.

Javadoc/: Full technical documentation for the project classes and methods.

.idea/: Project configuration for IntelliJ IDEA.

💻 Installation & Setup
Clone the repository:

Bash
git clone https://github.com/HughMorris01/Inventory_Management_Sys.git
Database Configuration: Ensure you have a MySQL instance running and update the database connection strings in the source code to match your environment.

Run the Application: Open the project in IntelliJ IDEA, ensure the JavaFX SDK is configured in your library settings, and run the Main class.

📝 Technical Implementation Details
During development, specific focus was placed on:

MVC Architecture: Decoupling the data models from the view logic and controllers for better maintainability.

Input Validation: Using Regular Expressions and conditional logic to ensure numerical data types and required fields are correctly handled before database commits.

Scalability: Designing the Inventory class as a central data hub to allow for easy expansion of the part/product relationship.

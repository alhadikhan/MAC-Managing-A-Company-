# MAC (Managing A Company)

MAC is a comprehensive Java-based management application designed to facilitate the efficient administration of various company functions. Built with a user-friendly graphical user interface (GUI), it offers seamless interaction and management capabilities across multiple domains including financial management, sales, production, human resources, and administrative tasks.

## Features

- **User Role Management**: Allows different access levels (CEO, Financial Manager, Sales Manager, Production Manager, HR Manager, Admin) with role-based permissions.
- **Data Management**: Integrates with a MySQL database (`jdbc:mysql://localhost:3306/mac`) to store and retrieve data related to employees, products, financial transactions, and more.
- **Module Descriptions**:
  - **CEO Module**: Provides an overview of company operations and financial insights.
  - **Financial Manager Module**: Manages financial records, including earnings, costs, and dues.
  - **Sales Manager Module**: Handles product sales, inventory, and revenue tracking.
  - **Production Manager Module**: Monitors production processes, inventory management, and product details.
  - **HR Manager Module**: Manages employee records, payroll, and HR-related tasks.
  - **Admin Module**: Administrates user roles, permissions, and system settings.

## Technologies Used

- **Java**: Core programming language for application development.
- **Swing**: GUI toolkit for building the application's user interface.
- **MySQL**: Relational database management system for data storage.
- **JDBC**: Java Database Connectivity API for connecting Java applications to databases.

## Usage

1. **Clone the Repository**:
   ```bash
   git clone [https://github.com/alhadikhan/MAC-Managing-A-Company-.git]
## Import into IDE

Open the project in your Java IDE (e.g., IntelliJ IDEA, Eclipse).

## Database Setup

1. Install MySQL and create a database named `mac`.
2. Update the database URL, username, and password in the source code (`DbConnection.java`).

## Compile and Run

1. Compile and run the main class `MAC.java` to start the application.
2. Log in with appropriate credentials based on the user role.

## Contributing

Contributions are welcome! If you have ideas for new features, improvements, or bug fixes, please open an issue or submit a pull request.


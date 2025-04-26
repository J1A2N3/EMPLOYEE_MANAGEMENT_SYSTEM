Employee Management System

Overview
The Employee Management System is a Java-based application designed to manage employee data. 
It includes features for handling employee tasks, leave, salary, and more. The system connects to a MySQL database for storing employee and related data.

Features
- Employee Login & Signup: Employees can securely log in using their user ID and password.
- Task Management: Employees can view and manage their tasks.
- Leave Management: Employees can request and view leave status.
- Salary Management: Employees can view salary details, including basic pay, bonus, deductions, and net salary.
- HR Dashboard: HR can manage employee data, approve sign-ups, and view performance reports.
- Feedback System: Employees can provide feedback.

Technologies Used
- Java: Core language used for application development.
- MySQL: Used for database management to store employee records.
- JDBC: Used for connecting the Java application with the MySQL database.
- Java Swing: Used for creating a graphical user interface (GUI).
- Eclipse IDE: Integrated development environment for the project.

Installation

1. Clone the Repository
bash
git clone https://github.com/your-username/employee-management-system.git


2. Set Up Database
1. Create a database `employee_management` in MySQL.
   ```sql
   CREATE DATABASE employee_management;
   ```

2. Set up tables like `employee`, `salary`, `tasks`, and `leave`.

3. Configure Database Connection
- Modify the `DatabaseConnection.java` file with your MySQL credentials.
  
```java
Connection connection = DriverManager.getConnection(
    "jdbc:mysql://localhost:3306/employee_management", "root", "password");
```

4. Import Project into Eclipse
- Import the project into your Eclipse IDE using **File** > **Import** > **Existing Projects into Workspace**.

5. Add Required Libraries
- Add the MySQL JDBC driver to your project build path.

6. Run the Application
- Run the `Main.java` class to start the application.

 Usage
1. Employee Login: Log in with your user ID and password.
2. HR Manager: Manage employee data, approve sign-ups, and view performance reports.

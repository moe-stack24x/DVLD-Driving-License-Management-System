🚗 DVLD – Driving License Management System

A desktop application built using C# Windows Forms to manage driving license services and related operations. The system provides an organized way to manage people, users, applications, tests, and driving licenses while applying software engineering principles and a structured architecture.

---

✨ Features

👤 People & User Management

- Add, update, delete, and search people.
- Complete User Management System (CRUD).
- Link each user to a single person record.
- User authentication and login validation.
- Account activation and deactivation using "IsActive".
- Current User tracking across the application.
- Remember Me functionality.

🚘 License Management

- Issue First-Time Driving Licenses.
- Renew Driving Licenses.
- Replace Lost or Damaged Licenses.
- Issue International Driving Licenses.
- View License Details and History.
- Detain and Release Licenses.

📝 Applications & Tests

- Manage application types, statuses, and fees.
- Manage driving license test types.
- Schedule test appointments.
- Record test results.
- Handle test retakes.

🖥️ User Interface

- Reusable User Controls.
- Search and filtering functionality.
- Event-driven communication between User Controls and Forms.
- Organized and user-friendly Windows Forms interface.

---

🏗️ Software Architecture & Design

The application follows Three-Tier Architecture, separating responsibilities into:

- Presentation Layer: Handles the user interface and user interactions.
- Business Layer: Contains business logic and application rules.
- Data Access Layer: Handles database operations and data retrieval.

The project also applies several Object-Oriented Programming concepts and focuses on code reusability and maintainability.

---

🛠️ Technologies Used

- C#
- .NET Framework
- Windows Forms
- SQL Server
- ADO.NET
- Visual Studio 2022
- Guna UI2

---

🎯 Learning Objectives

This project helped me gain practical experience in:

- Three-Tier Architecture.
- Object-Oriented Programming (OOP).
- Encapsulation, Inheritance, Composition, and Abstraction.
- Separation of Concerns (SoC).
- Reusability and Maintainability.
- Events and Delegates.
- Reusable User Controls.
- ADO.NET and CRUD Operations.
- SQL Server and Database Design.
- Implementing Business Rules.
- Building and maintaining a multi-layered desktop application.

---

🗄️ Database

The project uses Microsoft SQL Server.

The database scripts are available in the "DataBase" folder:

- "DrivingLicenseDB.sql"
- "DrivingLicenseDB_Full.sql"

The full database script contains the database objects and data, provided that the export was configured with Schema and data.

You can use the SQL scripts to set up the database in SQL Server Management Studio (SSMS).

---

📸 Screenshots

Screenshots of the application will be added here.

---

🚀 How to Run

1. Clone the repository:
   
   git clone https://github.com/moe-stack24x/DVLD-Driving-License-Management-System.git

2. Open the solution file (".sln") using Visual Studio 2022.

3. Open SQL Server Management Studio (SSMS).

4. Locate the database scripts in the "DataBase" folder and use the full database script to set up the database.

5. Configure the SQL Server connection string in the application settings according to your SQL Server instance.

6. Build and run the project using Visual Studio 2022.

---

👨‍💻 Author

Mohamed Idris

- GitHub: "moe-stack24x" (https://github.com/moe-stack24x)

---

<p align="center">
  Developed with dedication and a passion for software engineering ❤️
</p>

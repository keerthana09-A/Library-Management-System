This **Library Management System** is a technical solution developed to transition traditional manual record-keeping into a digital environment. It provides a centralized platform for librarians to manage book inventories, member profiles, and real-time transaction tracking (Issue/Return logic).

## 🚀 Key Features
* **Inventory Management:** Full **CRUD** (Create, Read, Update, Delete) functionality to manage book records including ISBN, author, and category.
* **Member Profiles:** Digital database for student/staff registration with unique identification and contact tracking.
* **Automated Transaction Logic:** Smart algorithms to handle book issuance, availability checks, and return processing.
* **Fine Calculation Engine:** Integrated mathematical logic to calculate overdue penalties based on predefined return policies.
* **Advanced Search & Filter:** Real-time search functionality allowing users to locate books by title, author, or genre.
* **Secure Admin Portal:** Restricted access to ensure only authorized personnel can modify the database.

## 🛠️ Technical Stack
* **Language:** Java (Core Java & Object-Oriented Programming)
* **Database:** MySQL / PostgreSQL (Relational Database Management)
* **Architecture:** Model-View-Controller (**MVC**) Design Pattern
* **Connectivity:** JDBC (Java Database Connectivity) for seamless DB interaction.
* **Tools:** IntelliJ IDEA / Eclipse, Git for Version Control.

## 📂 Project Structure
```text
├── src
│   ├── com.lms.model       # Entity classes (Book.java, Member.java)
│   ├── com.lms.controller    # Business logic & Services (IssueReturnService.java)
│   ├── com.lms.view          # Console or GUI-based interface components
│   ├── com.lms.database      # DB Connection utilities (DBHandler.java)
│   └── Main.java             # Application Entry Point
└── README.md
```

## ⚙️ Installation & Setup
1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/your-username/library-management-system.git
    ```
2.  **Database Configuration:** Import the provided `.sql` schema into your local MySQL server.
3.  **Credential Setup:** Update the `DBHandler.java` file with your local database username and password.
4.  **Build & Run:** Open the project in your preferred IDE and execute `Main.java`.





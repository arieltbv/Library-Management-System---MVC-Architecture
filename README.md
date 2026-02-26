Library Management System (LibPro) – MVC Architecture
A comprehensive system design and software engineering project focused on managing library operations using the MVC (Model-View-Controller) architectural pattern. This project covers the full product planning lifecycle, from stakeholder identification to detailed system modeling.

📌 Project Overview
The LibPro system is designed to streamline library services for readers, librarians, and managers. It ensures efficient book management, user tracking, and automated system actions.

🏗️ Architecture
The project is built on the MVC Pattern to ensure a clean separation of concerns:


Model: Represents the data and business logic (e.g., User, Book, Loan, Notification).


View: The user interface components for interacting with the system (e.g., Search pages, Management dashboards).


Controller: Manages user requests, processes logic, and coordinates between the Model and View.

👥 Key Stakeholders & Use Cases
The system defines four primary actors with specific permissions:

📖 Reader
Search for books by title, author, or category.

Request loan extensions.

Update personal contact information.

📚 Librarian
Manage book information (Add, Edit, Delete).

Manage user records and loan history.

Execute book borrowing and return processes.

👑 Manager
Generate statistical reports on library activity.

Export reports to PDF or Excel formats.

Manage and modify access permissions for librarians.

🤖 System (Automated)
Sends alerts before loan periods expire.

Processes automatic payments for late returns.

Blocks users automatically after repeated violations (e.g., 3+ late returns).

📊 System Design Diagrams
The project includes detailed technical modeling:


Use Case Diagrams: Mapping all user interactions.


Sequence Diagrams: Visualizing the flow of operations like "Book Search" and "Update Contact Info".


Class Diagrams: Defining the data structures and relationships.

🛠️ Technologies & Methodology

Pattern: Model-View-Controller (MVC).

Deliverables: Functional specifications, role-based permission design, and MVP scope definition.

Collaborative Tools: Iterative development cycles and team-based system modeling.

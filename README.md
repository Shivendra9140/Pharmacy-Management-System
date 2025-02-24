📖 About the Project

The Pharmacy Management System is a Java-based application designed to streamline pharmacy operations, including medicine stock management, sales tracking, and customer information handling. This system provides a user-friendly interface to help pharmacists efficiently manage inventory, suppliers, and transactions.

🚀 Features

User Authentication: Secure login for admin and staff.

Medicine Management: Add, update, delete medicine records.

Stock Management: Track medicine availability and low-stock alerts.

Sales & Billing: Generate invoices and process transactions.

Customer Management: Store and manage customer details.

Supplier Management: Keep track of medicine suppliers.

Reports & Analytics: View sales reports and stock levels.

Database Integration: Supports MySQL for data storage.

Graphical User Interface (GUI): Built with Java Swing
Steps to Run

Clone the repository

git clone https://github.com/yourusername/pharmacy-management-system.git
cd pharmacy-management-system

Import the project into your preferred Java IDE.

Set up the database:

Open MySQL and create a database:

CREATE DATABASE pharmacy_db;

Import the provided SQL file (database.sql) to set up tables.

Configure database connection:

Open dbConfig.java and update the database credentials.

Build and Run the Project:

If using Apache Ant:

ant build
ant run

Otherwise, compile and run Main.java directly from your IDE.
🛠️ Technologies Used

Programming Language: Java

Database: MySQL / SQLite

GUI Framework: Java Swing / JavaFX

Development Tools: NetBeans

Build Tool: Apache Ant

📥 Installation & Setup

Prerequisites

Ensure you have the following installed:

Java Development Kit (JDK) 8+

MySQL Database

NetBeans


🤝 Contributors

Your Name – Shivendra Pratap Singh

Other Team Members- Prerna Shukla, Himanshu Singh Kachwaha, Isha Dixit and Ramanshu Yadav

📜 License

This project is licensed under the MIT License.

🔮 Future Enhancements

Implement barcode scanning for faster checkout.

Add an online ordering module for customers.

Improve UI with modern JavaFX designs.

Implement a cloud-based database integration.

📝 Notes

Ensure that you have proper database configurations before running the system.

Modify config.properties or dbConfig.java for any required database changes.

If you encounter issues, check the logs or refer to the Troubleshooting section in the documentation.

Feel free to contribute and improve this project! 🚀

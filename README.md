**🐾 Menagerie Pet Database**
**📖 Features**
Database-Driven Design
A MySQL database with a single table, pet, designed to store information such as:
Pet name, species, and gender
Owner details
Birth and (optional) death dates

**Python Integration**
Scripts to interact with the MySQL database using Python.
Example scripts for common operations like:
Adding new pet records
Retrieving pet information
Updating or deleting records

**Pre-Populated Data**
Includes sample data for testing and demonstration.

**🛠️ Technologies Used**
Python: For database operations using the mysql-connector or SQLAlchemy library.
MySQL Workbench: For database design and visualization.
MySQL Server: Version 8.0 or later, as required by the dump file provided.

**🚀 Getting Started**
**Prerequisites**
**Install Python:**
Download and install Python (3.8 or later) from python.org.
**Install MySQL Server and Workbench:**
Download MySQL from mysql.com.
Install MySQL Workbench for visual database management.
**Install Python Libraries:**
Use pip to install the required library:
bash
Copy
Edit
pip install mysql-connector-python

📊 **Database Schema**

The database schema for the pet table is as follows:

scss

+----------+--------------+-----------------------------------------------+
| Column   | Data Type    | Description                                   |
+----------+--------------+-----------------------------------------------+
| name     | VARCHAR(20)  | The name of the pet.                         |
| owner    | VARCHAR(20)  | The name of the pet's owner.                 |
| species  | VARCHAR(20)  | The species of the pet (e.g., cat, dog).     |
| sex      | CHAR(1)      | The gender of the pet ('m', 'f', or NULL).   |
| birth    | DATE         | The birth date of the pet.                   |
| death    | DATE         | The date of death for the pet (if applicable).|
+----------+--------------+-----------------------------------------------+
**🛠 Installation**
Clone the Repository:

bash
Copy
Edit
git clone https://github.com/yourusername/menagerie-pet-database.git
cd menagerie-pet-database
**Set Up the Database:**

Open MySQL Workbench and connect to your local MySQL server.
Import the menagerie.sql dump file provided in the /database folder:
sql
Copy
Edit
SOURCE path/to/menagerie.sql;
**Run the Python Script:**

Use the example Python script (main.py) to interact with the database:
bash
Copy
Edit
python main.py

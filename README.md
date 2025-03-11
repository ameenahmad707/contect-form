# Contact Form

This is a **fully functional contact form** built with **HTML, CSS, and PHP**. It includes real-time validation and stores messages directly into a MySQL database.

## Features
- ✅ Responsive design
- ✅ Real-time validation with JavaScript
- ✅ Stores messages in a MySQL database
- ✅ Secure input handling with PHP

## Setup Instructions

### 1. Clone the Repository
```sh
git clone https://github.com/ameenahmad707/contect-form/tree/main/Contect%20Form
```

### 2. Create the Database
Run the following SQL query to create the `contacts` table:
```sql
CREATE TABLE contacts (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(255) NOT NULL,
    email VARCHAR(255) NOT NULL,
    subject VARCHAR(255) NOT NULL,
    message TEXT NOT NULL,
    created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);
```

### 3. Configure Database Connection
Edit `save_contact.php` and update these lines with your database details:
```php
$servername = "localhost";
$username = "your_db_user";
$password = "your_db_password";
$dbname = "your_database";
```

### 4. Deploy on a Server
- Use **XAMPP** or **MAMP** for local testing
- Upload files to a **PHP-supported hosting** like cPanel or InfinityFree

## Usage
1. Fill out the contact form.
2. Click "Send Message".
3. The data will be stored in your database.

## License
This project is open-source and free to use!

---

Feel free to reach out if you need help! 😊


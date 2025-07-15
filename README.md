---

## Setup Instructions

### Prerequisites

Ensure the following are installed on your system:

- PHP (version 8.0 or higher)
- Composer (PHP dependency manager)
- Node.js (version 16 or higher)
- npm (Node.js package manager)
- SQLite (database)

---

### Steps to Set Up the Application

#### 1. Clone the Repository

```bash
git clone <repository-url>
cd <repository-folder>
2. Install PHP Dependencies
bash
Copy
Edit
composer install
3. Install Node.js Dependencies
bash
Copy
Edit
npm install
4. Set Up the SQLite Database
Create a new SQLite database file:

bash
Copy
Edit
touch database/database.sqlite
Update the .env file with the correct database configuration:

ini
Copy
Edit
DB_CONNECTION=sqlite
DB_DATABASE=/absolute/path/to/database/database.sqlite
Run migrations to set up the database schema:

bash
Copy
Edit
php artisan migrate
5. Start the Development Server
Run the Laravel server:

bash
Copy
Edit
php artisan serve
Optionally, compile assets using the Node development server:

bash
Copy
Edit
npm run dev
Access the Application
Once the servers are running, open your browser and visit:

cpp
Copy
Edit
http://127.0.0.1:8000
Notes
Ensure proper write permissions for the database/database.sqlite file.

If deploying the application, update your .env file with production environment settings.

For email notifications, configure valid SMTP credentials in the .env file (e.g., using Mailtrap, Gmail SMTP, etc.).
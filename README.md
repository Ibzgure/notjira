# The Challenge

☑️ **Develop a task management system as a software engineer.**

---

## Requirements

- Add, edit, or delete users as an administrator.
- Assign tasks to users and set deadlines for each task.
- Include task statuses: **Pending**, **In Progress**, or **Completed**.
- Allow users to view tasks assigned to them and update task statuses.
- Send email notifications to users when new tasks are assigned.

---

## Instructions

- Use PHP or a PHP framework (e.g., Laravel), but avoid CMS or JavaScript frameworks like Vue.js.
- Notify us if you plan to use any other framework (optional).
- Provide an SQL dump file and specify the database used if applicable.
- Demonstrate OOP skills (optional but recommended).
- Use JavaScript (Vanilla JS or Vue.js) to enhance the interface (recommended).
- Host the application and share the URL (recommended).
- Complete the challenge within **4 days**, submitting by **midday Tuesday, July 15th, 2025**.

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

## 1. Clone the Repository

```bash
git clone <repository-url>
cd <repository-folder>

---

## 2.Install PHP Dependencies

```bash
composer install
## 3.Install Node.js Dependencies

```bash
npm install
## 4.Set Up the SQLite Database
○Create a new SQLite database file:
```bash
touch database/database.sqlite
○Update your .env file to include:
DB_CONNECTION=sqlite
DB_DATABASE=/absolute/path/to/database/database.sqlite

○Run migrations to set up the database schema:
```bash
php artisan migrate
## 5.Start the Development Server
○Run the Laravel server:

```bash
php artisan serve
○Optionally, start the Node.js development server for assets:

```bash
npm run dev
## 6.Access the Application
○Open your browser and navigate to http://127.0.0.1:8000.

##Notes
-Ensure proper write permissions for database/database.sqlite.

-For production hosting, configure .env for your production database and URL.

-To enable email notifications, update .env with SMTP credentials:
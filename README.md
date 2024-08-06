Here's a more concise and straightforward GitHub description:

---

# Online Examination System

An efficient and user-friendly online exam system built with PHP and MySQL.

## Features

### Admin
- **User Management:** Create, update, delete user accounts.
- **Quiz Management:** Create and manage multiple-choice quizzes.
- **Monitoring:** Track ongoing exams.
- **Reports:** View detailed performance reports.

### Students
- **Easy Interface:** Simple navigation for taking exams.
- **Timed Quizzes:** Simulate real exam conditions.
- **Instant Results:** Get immediate feedback.
- **History:** Review past quiz attempts and scores.

## Tech Stack
- **Frontend:** HTML, CSS, Bootstrap
- **Backend:** PHP, MySQL
- **JavaScript:** jQuery, AJAX

## Installation

1. **Clone the repo:**
   ```bash
   git clone https://github.com/yourusername/online-examination-system.git
   ```
2. **Navigate to the project:**
   ```bash
   cd online-examination-system
   ```
3. **Setup database:**
   - Create a database named `project`.
   - Import `project.sql` from the `database` folder.
4. **Configure database connection in `dbConnection.php`:**
   ```php
   $con = new mysqli('localhost', 'root', '', 'project');
   ```
5. **Run on localhost:**
   - Start your server (e.g., XAMPP, WAMP).
   - Open `http://localhost/online-examination-system` in your browser.

## Usage

### Admin Login
- Default credentials: 
  - Username: `admin`
  - Password: `admin`

### Student Registration
- Students can register and log in to take quizzes.

## Contribution
Contributions are welcome! Submit a pull request or open an issue for suggestions.

## License
MIT License. See the [LICENSE](LICENSE) file.

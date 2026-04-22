🎯 JobHunt - Professional Job Portal Platform

JobHunt is a comprehensive web-based job portal application designed to connect employers with job seekers. Built with a modern tech stack, it features a clean UI, robust job management, and an integrated quiz system for candidate screening.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Version](https://img.shields.io/badge/version-1.0.0-green.svg)
![PHP](https://img.shields.io/badge/PHP-8.x-purple.svg)
![MySQL](https://img.shields.io/badge/MySQL-8.0-blue.svg)

✨ Key Features

- **💼 Job Management:** Employers can post, edit, and manage job listings.
- **🔍 Advanced Search:** Job seekers can filter jobs by category, location, and type.
- **📄 PDF Generation:** Automatic resume/application generation in PDF format.
- **📝 Skill Quizzes:** Integrated quiz system for employers to screen applicants.
- **🏢 Company Profiles:** Detailed company listings with logos and descriptions.
- **📱 Responsive Design:** Fully optimized for mobile, tablet, and desktop viewing.

 🚀 Tech Stack

- **Frontend:** HTML5, CSS3 (Remix Icons, Google Fonts), JavaScript
- **Backend:** PHP (PDO for secure database interactions)
- **Database:** MySQL / MariaDB
- **Tools:** PDF Generator (PHP), GSAP for animations

 🛠️ Installation & Setup

 Prerequisites
- [XAMPP](https://www.apachefriends.org/) (Apache & MySQL)
- A modern web browser

 Steps
1. **Clone/Download:** Place the project folder in your XAMPP directory: `C:\xampp\htdocs\Jobhunt`.
2. **Database Setup:**
   - Open MySQL Workbench or phpMyAdmin.
   - Run the [jobhunt.sql](jobhunt.sql) script to create the database and tables.
   - *Alternatively*, visit `http://localhost/Jobhunt/setup.php` in your browser for automated setup.
3. **Configuration:** Check [config.php](config.php) to ensure your database credentials are correct:
   ```php
   define('DB_HOST', 'localhost');
   define('DB_USER', 'root');
   define('DB_PASS', '');
   define('DB_NAME', 'jobhunt');
   ```
4. **Access Project:** Open your browser and navigate to `http://localhost/Jobhunt/index.php`.

👤 Sample Credentials

| Account Type | Email | Password |
| :--- | :--- | :--- |
| **Administrator** | `admin@jobhunt.com` | `password123` |

 📂 Project Structure

- `/assets` - Images, logos, and external CSS/JS libraries.
- `/api` - Backend logic for dynamic interactions.
- `/pdfs` - Generated application documents.
- `setup.php` - Automated database initialization tool.
- `job-quiz.php` - Candidate assessment module.

📝 License
This project is licensed under the MIT License.

*Developed with ❤️ for the community.*

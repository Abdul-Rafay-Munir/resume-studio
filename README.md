# Resume-Studio

[![Built With: PHP](https://img.shields.io/badge/Built%20With-PHP-blue)]()
[![Database: MySQL](https://img.shields.io/badge/Database-MySQL-orange)]()
[![Server: XAMPP](https://img.shields.io/badge/Server-XAMPP-lightgrey)]()

Resume-Studio is a PHP + MySQL project built on **XAMPP**, allowing users to create, store, and generate formatted resumes using professionally styled templates.  
It is lightweight, beginner-friendly, and fully customizable.

---

## 🚀 Features

<<<<<<< HEAD
- PHP-based resume builder
- Stores all data in MySQL
- Template-based resume generation
- Supports multiple resume entries
- Easy to run on XAMPP (Apache + MySQL)
- Simple folder structure, easy to modify
=======
- PHP-based resume builder  
- Stores all data in MySQL  
- Template-based resume generation  
- Supports multiple resume entries  
- Easy to run on XAMPP (Apache + MySQL)  
- Simple folder structure, easy to modify  
>>>>>>> 06aa8ac27dca1204de532104ff7d24f9fb480ba8
- Optional PDF export support (via Dompdf)

---

## 📁 Project Structure

```

resume-studio/
│
├── index.php                # Start page / form input
├── dashboard.php            # Manage saved resumes
├── create_resume.php        # Generates resume using template
│
<<<<<<< HEAD
├── resume_builder.sql    # MySQL database schema
=======
├── resume_builder_db.sql    # MySQL database schema
>>>>>>> 06aa8ac27dca1204de532104ff7d24f9fb480ba8
│
├── includes/                # Config + shared PHP components
│   ├── config.php           # Database credentials
│   ├── db.php               # DB connection file
│   └── helpers.php          # Utility functions
│
├── templates/               # Resume templates (HTML/CSS)
│   ├── template1.php
│   ├── template2.php
│   └── assets/              # Images/CSS for templates
│
├── process/
│   └── save_resume.php      # Handles form submission
│
└── dompdf/ (optional)       # PDF export library if enabled

<<<<<<< HEAD
```
=======
````
>>>>>>> 06aa8ac27dca1204de532104ff7d24f9fb480ba8

---

## ⚙️ Requirements

<<<<<<< HEAD
- **XAMPP** (7.x / 8.x)
- **PHP 7.4+ or PHP 8.x**
- **MySQL** (via XAMPP)
- Apache enabled
- PHP extensions enabled:
  - `mysqli`
  - `mbstring`
=======
- **XAMPP** (7.x / 8.x)  
- **PHP 7.4+ or PHP 8.x**  
- **MySQL** (via XAMPP)  
- Apache enabled  
- PHP extensions enabled:  
  - `mysqli`  
  - `mbstring`  
>>>>>>> 06aa8ac27dca1204de532104ff7d24f9fb480ba8
  - `gd` (optional, for PDF/image support)

---

## 🛠️ Installation (XAMPP)

### 1. Clone or download the repository
<<<<<<< HEAD

```bash
git clone https://github.com/Abdul-Rafay-Munir/resume-studio.git
```
=======
```bash
git clone https://github.com/Abdul-Rafay-Munir/resume-studio.git
````
>>>>>>> 06aa8ac27dca1204de532104ff7d24f9fb480ba8

### 2. Move the project into XAMPP `htdocs`

```
C:\xampp\htdocs\resume-studio\
```

### 3. Start Apache & MySQL from XAMPP Control Panel

### 4. Create and import the database

<<<<<<< HEAD
- Open: `http://localhost/phpmyadmin`
- Create a database (example: `resume_studio`)
- Import:
=======
* Open: `http://localhost/phpmyadmin`
* Create a database (example: `resume_studio`)
* Import:
>>>>>>> 06aa8ac27dca1204de532104ff7d24f9fb480ba8

```
resume_builder_db.sql
```

### 5. Configure database settings

Edit:

```
includes/config.php
```

Example:

```php
$host = "localhost";
$user = "root";
$pass = "";
$db   = "resume_studio";
```

### 6. Run the project

Open in your browser:

```
http://localhost/resume-studio/
```

---

## 🎯 Usage

<<<<<<< HEAD
- Open the homepage and fill your resume information
- Save resume → data is stored in MySQL
- Choose a template from `/templates/`
- `create_resume.php` generates clean formatted output
- Optionally export to PDF (if Dompdf is installed)
=======
* Open the homepage and fill your resume information
* Save resume → data is stored in MySQL
* Choose a template from `/templates/`
* `create_resume.php` generates clean formatted output
* Optionally export to PDF (if Dompdf is installed)
>>>>>>> 06aa8ac27dca1204de532104ff7d24f9fb480ba8

---

## 🗄 Database Schema Overview

`resume_builder_db.sql` consists of tables such as:

<<<<<<< HEAD
- `personal_info` — name, contact, summary
- `education` — degree, institution, duration
- `experience` — job history
- `skills` — skill sets
- `resumes` — links resume sections together
=======
* `personal_info` — name, contact, summary
* `education` — degree, institution, duration
* `experience` — job history
* `skills` — skill sets
* `resumes` — links resume sections together
>>>>>>> 06aa8ac27dca1204de532104ff7d24f9fb480ba8

You can extend schema as needed.

---

## 🎨 Customization

### ➤ Add New Templates

Simply create a new file inside:

```
templates/
```

For example:

```
template3.php
```

### ➤ Add New Resume Fields

Modify:

<<<<<<< HEAD
- `index.php`
- `process/save_resume.php`
- Database tables accordingly
=======
* `index.php`
* `process/save_resume.php`
* Database tables accordingly
>>>>>>> 06aa8ac27dca1204de532104ff7d24f9fb480ba8

---

## 🔮 Future Improvements

<<<<<<< HEAD
- Add user authentication
- More resume templates
- Live preview mode
- Modern UI redesign (Bootstrap/Tailwind)
- API-based version
- Enhanced PDF export
=======
* Add user authentication
* More resume templates
* Live preview mode
* Modern UI redesign (Bootstrap/Tailwind)
* API-based version
* Enhanced PDF export
>>>>>>> 06aa8ac27dca1204de532104ff7d24f9fb480ba8

---

## 🤝 Contributing

Pull requests are welcome.
You can contribute by adding templates, improving UI, optimizing database structure, or enhancing functionality.

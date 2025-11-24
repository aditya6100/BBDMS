# BBDMS (Blood Bank Donor Management System)

## 🚀 Overview
BBDMS (Blood Bank Donor Management System) is a web-based application developed to manage blood donation processes efficiently. It provides functionalities for donors to register, for users to search for available blood, and for the system to manage donor information and blood requests. The system aims to streamline operations for blood banks and facilitate faster access to blood for those in need.

## ✨ Features
-   **Donor Registration:** Allows new donors to register their information.
-   **Blood Search:** Users can search for available blood based on blood group and location.
-   **Donor List:** Displays a list of registered donors.
-   **Request for Blood:** Functionality for recipients or hospitals to request blood.
-   **User Authentication:** Secure login and logout for donors/users and potentially administrators.
-   **Profile Management:** Donors/users can view and update their profiles.
-   **Password Management:** Functionality to change user passwords.

## 🛠️ Technologies Used
-   **Backend:** PHP
-   **Database:** MySQL
-   **Frontend:** HTML, CSS, JavaScript
-   **Web Server:** Apache or Nginx
-   **Version Control:** Git, GitHub

## ⚙️ Installation
To get a local copy up and running, follow these simple steps.

### Prerequisites
-   XAMPP or WAMP server (includes Apache, MySQL, PHP)
-   Git

### Setup
1. Clone the repo
   ```bash
   git clone https://github.com/aditya6100/BBDMS.git
   ```
2. Navigate to the project directory
   ```bash
   cd BBDMS
   ```
3. Copy project files to your web server's document root
   *   Move the contents of the cloned repository into your XAMPP's `htdocs` folder or WAMP's `www` folder (e.g., `C:\xampp\htdocs\bbdms`).
4. Import the database
   *   Start Apache and MySQL from your XAMPP/WAMP control panel.
   *   Open phpMyAdmin (usually via `http://localhost/phpmyadmin`).
   *   Create a new database (e.g., `bbdms_db`).
   *   Import the provided SQL dump (if available, usually named `bbdms.sql` or similar) into your newly created database.
5. Configure database connection
   *   Locate the database connection file in your project (e.g., `config.php`, `db_connect.php`, or similar) and update with your MySQL database credentials (hostname, username, password, database name `bbdms_db`).

## 🚀 Usage
1.  Ensure Apache and MySQL are running in your XAMPP/WAMP control panel.
2.  Open your web browser and navigate to the project's URL (e.g., `http://localhost/bbdms`).
3.  Register as a donor or log in to access the system's features.
4.  Utilize the search functionality to find blood or manage donor/recipient requests.

## 🤝 Contributing
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! ⭐

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'feat: Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License
Distributed under the MIT License. See `LICENSE` for more information. (Assuming an MIT License; create a LICENSE file if none exists).

## 📞 Contact
Aditya Bhanudas Patil - [aditya.patil.dev@example.com](mailto:aditya.patil.dev@example.com) (Please replace with your actual email/LinkedIn)
Project Link: [https://github.com/aditya6100/BBDMS](https://github.com/aditya6100/BBDMS)
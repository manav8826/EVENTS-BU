🎉 EVENTS@BU – Unified Club Portal for Bennett University

Developed by:
Manav Gupta (E22CSEU1736)
Yasharth Singh (E22CSEU1391)

Mentored by:
Mrs. Akansha Singh (Professor, SCSET)

📌 About the Project

EVENTS@BU is a centralized web portal designed to unify all student clubs at Bennett University. The platform streamlines communication, event management, and participation tracking, fostering a collaborative and vibrant campus culture.

🚀 Tech Stack
Category	Technology
🧠 Frontend	HTML, CSS, JavaScript
🌐 Backend	PHP
🗄️ Database	MySQL
🎨 UI/UX	Bootstrap (optional)
🧪 Testing	Manual / User-based
🌍 Hosting	TBD (based on deployment)
🧰 Features Overview

Unified Club Platform: All student clubs integrated into a single portal

Event Calendar: Real-time events with countdown timers

Leaderboards: Track participation and achievements

Club Registration: Easy registration & approval workflow

User Management: Admin panel for organizers & members

Notifications: Event announcements and result tracking

## 📷 Screenshots

![Dashboard View](https://github.com/manav8826/EVENTS-BU/raw/my-new-branch/1713675778186.jpeg)  
![Event Page View](https://github.com/manav8826/EVENTS-BU/raw/my-new-branch/1713675778919.jpeg)





⚙️ Local Setup Instructions
1. Clone the Repository
git clone https://github.com/manav8826/EVENTS-BU.git
cd EVENTS-BU

2. Set Up Local Server

This project uses PHP. Recommended tools:

XAMPP (Windows)

WAMP (Windows)

MAMP (Mac)

Using XAMPP:

Place the project folder inside htdocs.

Start Apache and MySQL from the XAMPP Control Panel.

3. Set Up Database

Open phpMyAdmin (http://localhost/phpmyadmin).

Create a new database, e.g., events_bu.

Import the SQL file from the repository (if provided).

Update DB credentials in includes/db.php or config.php as per your setup.

4. Run the Project

Open your browser and go to:

http://localhost/EVENTS-BU/
```bash
📂 Project Structure
EVENTS-BU/
├── index.php                 # Landing page
├── register.php              # User registration
├── login.php                 # User login
├── dashboard/                # Protected dashboard for logged-in users
│   ├── events.php            # Event listings
│   ├── leaderboard.php       # Participation leaderboard
│   └── profile.php           # User profile management
├── includes/                 # Reusable components & configs
│   ├── db.php                # Database connection
│   ├── header.php            # Common header file
│   └── footer.php            # Common footer file
├── css/                      # Stylesheets
│   └── style.css
├── js/                       # JavaScript scripts
│   └── main.js
├── images/                   # Project images & screenshots
└── README.md                 # Project documentation


🔹 Tip: Keep includes/ for shared code, dashboard/ for authenticated user pages, and css/js/images organized for maintainability.

🙋 Frequently Asked Questions

Q1: Can I participate in multiple clubs?
Yes! Students are encouraged to join and engage with multiple clubs.

Q2: How do I track event results?
Check the Leaderboard section for real-time updates.

Q3: How do I register for a club?
Visit a club’s profile page and click the Join button.

👥 Contributing

Want to improve the project? Follow these steps:

Fork the repository

Create a new branch

git checkout -b feature-name


Make your changes

Commit your changes

git commit -m "Added new feature"


Push your branch

git push origin feature-name


Open a pull request

📬 Contact & Feedback

Email: manavgupta8527@gmail.com

GitHub: Open issues or PRs for feedback

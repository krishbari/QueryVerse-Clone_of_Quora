# QueryVerse-Clone_of_Quora
QueryVerse: A Quora-inspired Q&amp;amp;A platform clone. Share knowledge, ask questions, and engage with the community on this open-source Question and Answer website. QueryVerse is a web-based system that connects users to a community-driven knowledge-sharing platform.

============================================================================================================================================================================

•	Our project is focused on developing an "Online Question and Answer Doubt Solving Website." This platform is designed to cater to a diverse audience, including students, professionals, and anyone seeking answers to their questions and doubts. The project aims to foster knowledge-sharing and collaboration within a user-friendly digital environment. QueryVerse is an innovative online platform developed by a team of dedicated individuals who aim to provide an efficient and user-friendly solution to address users' questions and doubts across various topics. The project team consists of web developers, UI/UX designers, and domain experts. The platform is designed to facilitate knowledge sharing and community engagement.



----------Installation----------

=====> Password for zip file: queryverse <=====

1. Download and Install XAMPP: (Requires specific version xampp-windows-x64-7.4.3-0-VC15)
If you haven't already, download and install XAMPP from the official website: XAMPP. Follow the installation instructions for your operating system.
Direct link: https://sourceforge.net/projects/xampp/files/XAMPP%20Windows/7.4.3/xampp-windows-x64-7.4.3-0-VC15-installer.exe/download

2. Clone or Download the Project:
Clone the QueryVerse project repository or download the project files if you haven't already.

3. Move Project Files to XAMPP htdocs:
Copy or move all the project files to the XAMPP htdocs directory. The htdocs directory is typically located in your XAMPP installation folder. On Windows, it's often at 'C:\xampp\htdocs'.
Place your QueryVerse project files in a separate folder inside htdocs, e.g., 'C:\xampp\htdocs\projects\queryverse' (Windows) .

4. Start XAMPP:
Open XAMPP Control Panel and start the Apache and MySQL services.

5. Database Setup:
Open your web browser and go to http://localhost/phpmyadmin/ to access the phpMyAdmin interface.
Create a new MySQL database for your project (e.g., "queryverse"). Remember the database name, as you'll need it in your project configuration.
Import or execute the SQL scripts necessary to set up your database schema and initial data. Your project's documentation or setup instructions should provide details on this step.
Database Already given in project zip file.

6. Configure PHP Settings:
Update your project's PHP configuration, if required. Ensure that the php.ini and phpMyAdmin settings match your project's needs. Check for variables like max_execution_time, upload_max_filesize, and post_max_size, and adjust them as necessary.

7. Update Project Configuration:
Open your project's configuration files (e.g., config.php) and update the database connection settings to point to your newly created MySQL database.

php code
$dbHost = 'localhost';
$dbUser = 'root';
$dbPass = '';
$dbName = 'queryverse'; // Use the database name you created

8. Access QueryVerse:
Open your web browser and navigate to http://localhost/projects/queryverse (or the appropriate URL where you placed your project files). You should now be able to access and use QueryVerse on your local XAMPP server.



----------Documentation and Diagrams----------
Comprehensive project documentation and system diagrams are available to help you understand and contribute to QueryVerse effectively. These resources provide insights into the project's architecture, design decisions, and workflow. Whether you're a developer looking to dive into the codebase or a user interested in understanding the platform's features, our documentation and diagrams have you covered.

o API Documentation
o System Diagrams
o User Guides



----------Description of the system----------
The system will consist of various web pages and modules, including:
o	Guest Homepage
o	Login/Registration Page
o	Admin Page
o	Admin Login
o	User Login
o	Index Homepage
o	Trending Topics
o	Questions Page
o	User Profile
o	User Settings
o	Admin Dashboard
o	About us 
o	Contact us
o	Leaderboard



----------Proposed System----------

•	Guest Homepage:
Welcome message and brief introduction.
Search bar for quick topic or question access.
Featured questions or topics.
User registration and login options.
•	Login/Registration Page:
User registration form with fields for username, email, password, and profile picture.
Login form for existing users with username/email and password.
"Forgot Password" feature.
Social media login options for convenience.
•	Index Homepage:
User dashboard displaying recent questions, answers, and trending topics.
Notifications and updates.
Quick access to user profile, settings, and question posting.
Trending topics sidebar.
•	Trending Topics:
A dynamic list of trending topics based on user interactions.
Each topic links to related questions and discussions.
•	Questions Page:
Search bar and filters for topic-specific questions.
List of questions, sorted by relevance or recent activity.
User-friendly question layout with options to upvote, downvote, comment, and share.
Option to mark questions as "answered" and archive them.
•	User Profile:
User's profile picture and personal information.
List of questions and answers contributed by the user.
Activity feed showing user interactions.
Statistics on reputation, badges, and contributions.
Edit profile and privacy settings.
•	User Settings:
Account settings to manage username, email, and password.
Notification preferences to control email or in-site notifications.
Privacy settings for profile visibility.
Option to connect/disconnect social media accounts.
Delete account option.
•	Admin:
Dashboard for administrators with access to user management, content moderation, and site statistics.
•	User management: 
User roles, suspension, and removal.
Content moderation tools for questions, answers, and comments.
Analytics and reporting for user activity and site performance.
•	About Us:
Information about the QueryVerse team, mission, and vision.
Overview of the website's history and goals.
Team member profiles.
•	Contact Us: -
Contact form for user inquiries and feedback. 
Email address and contact details for support.
•	Leaderboard:
Ranking of top users based on contributions, reputation, and engagement.
User-friendly leaderboard layout with user avatars and scores.



----------Technologies Used----------
•	Languages : Php, Html
•	Database System : MySQL

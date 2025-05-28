How to Run the Notice Board System?
Follow these steps to run the web-based Notice Board System (HTML, CSS, JavaScript, PHP, and MySQL):

Requirements
- XAMPP / WAMP / any local web server
- Web browser
- MySQL Database

 Setup Instructions
1.Download or Clone the Project:
git clone https://github.com/your-username/notice_board.git

2.Move to Web Server Directory
Copy the project folder to your web server directory:
htdocs/ (XAMPP) or www/ (WAMP)
3.Create the Database

Open phpMyAdmin

Create a new database (e.g., notice_board)

Import the provided .sql file from the project folder

4.Configure Database Connection
Open config.php or db.php (whichever handles connection)
Set the correct values:
$host = 'localhost';
$user = 'root';
$pass = '';
$dbname = 'notice_board';

Run the System
Start Apache and MySQL from XAMPP/WAMP
Open your browser and go to:
http://localhost/notice_board/

Group members:
 - Mary Miles A. Leonardo

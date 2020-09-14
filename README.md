# Student-Hostel-Management-System
Thisproject is developed with MySQL and Java. I used NetBeans IDE 8.0.2 to develop this project.

### Features of this Project:
- The Hostel Manager can SignUP (manually for security purpose)
- Only those students can LogIn to this system who are registered by the Hostel Manager
- Hostel Manager can:
  1. Insert a new Students Personal Info
  2. Insert or Update students Meal Info
  3. Insert or Update students Room No
  4. Update class info
  5. Insert student complain box so that students can raise a complain
  6. See all information of a particular student
  7. Delete any student account
  8. See how many students live in a particular room
  9. See total count of students who are registered in the system
- A registered student can:
  1. Raise a complain
  2. See the bill status for Meal
  
### How to Run this project:
You have toinstall **NetBeans IDE**. Then install **MySQL**. Then create a database named `DBProject1`

***Here is my Driver code to connect this project with MySQL:***
`Class.forName("com.mysql.jdbc.Driver");
String path="jdbc:mysql://localhost/DBProject1";
String user="root";
String pass="123456";`

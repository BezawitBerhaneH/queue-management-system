# queue-management-system
Queue Management System - README
 Queue Management System
 A web-based Queue Management System for hospitals, designed to reduce patient
 waiting time, manage appointments efficiently, and enhance service delivery through
 digital queue management.
 Features- Appointment scheduling with priority handling- Patient login and registration- Automatic queue number generation- SMS notifications for queue updates- Role-based access (Admin, Receptionist, Doctor, Patient)- Real-time queue monitoring and patient tracking- Department transfer functionality- Emergency case prioritization- Report generation for management
 Technologies Used- Frontend: HTML, CSS, JavaScript- Backend: PHP- Database: MySQL- Server: Apache (XAMPP)- Tools: Figma (prototyping), PlantUML, draw.io
 Project Structure
QMS/
 Queue Management System - README
 ├── css/
 ├── js/
 ├── php/
 ├── includes/
 ├── db/
 │   └── config.php
 ├── dashboard/
 ├── login.php
 ├── register.php
 ├── README.md
 └── index.html
 How to Run the Project Locally
 1. Clone the repository
   git clone https://github.com/yourusername/queue-management-system.git
 2. Move the folder to C:/xampp/htdocs/ if using XAMPP
 3. Start Apache and MySQL from XAMPP control panel
 4. Create a database
   - Go to phpMyAdmin
   - Create a new database (e.g. qms_db)
   - Import the provided .sql file (in db/ folder)
Queue Management System - README
 5. Configure database settings
   - Open db/config.php
   - Update your database credentials (host, user, password, dbname)
 6. Access the system
   Open your browser and go to: http://localhost/QMS/
 User Roles and Responsibilities
 Role         | Description-------------|-------------------------------------------------------------
Admin        | Manages users, departments, and oversees the system
 Receptionist | Registers patients, assigns queue numbers, generates reports
 Doctor       | Views and manages patient queues, transfers patients
 Patient      | Registers, books appointments, views queue status
 Known Limitations- No multi-language support- Limited to web version (no mobile app)- SMS feature may require third-party integration setup
 License
 This project is licensed under the MIT License.
 Author
Bezawit Berhane
 Queue Management System - README
 Computer Science Intern | Web Developer
 Reach out for collaboration or contributions!

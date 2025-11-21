**Hospital Management System** 
Hospital Management System using MySQL, Php and Bootstrap

Prerequisites:

1)Install XAMPP web server.
2)Any Editor (VS Code or Sublime Text)
3)Any web browser with latest version.

Languages and Technologies used in HMS:

1) HTML5 And CSS3
2) JavaScript (to update and craete dynamic content)
3) Bootstrap (HTML, CSS, and JS library)
4) XAMPP (downlod from a website Apache Friends)
5) Php
6) MySQL (RDBMS that uses SQL)
7) TCPDF (Generate PDFs)
   
Steps to run the project in Machine:

1) Download and install XAMPP in your machine
2) Clone or download the repository
3) Extract all the files and move it to the 'htdocs' folder of your XAMPP directory.
4) Start the Apache and Mysql in your XAMPP control panel.
5) Open your web browser and type 'localhost/phpmyadmin'
6) In phpmyadmin page, create a new database from the left panel and name it as 'myhmsdb'
7) Import the file 'myhmsdb.sql' inside your newly created database and click ok.
8) Open a new tab and type 'localhost/foldername' in the url of your browser


SOFTWARES USED:

1) XAMPP was installed on the Windows machine and APACHE2 Server and MySQL were initialized. And, files were built inside opt/lampp/htdocs/myhmsp
2) Visual Code used as a text editor.
3) Google Chrome
<--------------------------------The ‘Home’ page consists of 3 modules: ----------------------------------->

Patient Module
Doctor Module
Admin Module
Patient Module: This module allows patients to create their account, book an appointment to see a doctor and see their appointment history. The registration page(in the home page itself) asks patients to enter their First Name, Last Name, Email ID, Contact Number, Password and radio buttons to select their gender.

Book his/her appointment: Here, the patients can able to book their appointments to see a doctor. The appointment form requires patients to select the doctor that they want to see, Date and Time that they want to meet with the doctor. The consultancy fee will be shown accordingly to the patient as it was already determined by the doctor.

View patients, Appointment History: Here, the patient can see their appointment history which contains Doctor Name, Consultancy Fee, Appointment Date and Time.

*******************************************************************************************************************************************************************************************************************

Doctor Module:The doctors can login into their account which can be done by toggling the tab from ‘Patient’ to ‘Doctor’. Registration of a doctor account can be done only by admin. We will discuss more about this in Admin Module.

*******************************************************************************************************************************************************************************************************************

Admin Module: This module is the heart of our project where an admin can see the list of all patients. Doctors and appointments and the feedback/queries received from the ‘Contact’ page. Also admin can add doctor too. Login into admin account can be done by toggling into admin tab of the Home page. login page for admin. username: admin, password: admin123

**This module allows admin to perform five major operations:

1) View the list of all patients registered:
2) View the list of all doctors registered:
3) View the Appointment lists:
4) Add Doctor:
5) View User’s feedback/Queries:

**Updates

1) Cancel Appointments
Patients and doctors can able to delete their appointments.

Similarly doctors can also delete their appointments and patients can view their updated appointment details.

2) Remove Doctors by Admin

Admin can also delete the doctors from the system. This let admin to have more control over the system.

**Need to work on:**

Ability to accept the appointment by the doctor to acknowledge the patient that their appointment has been approved.
User should not be allowed to register if he/she tries to provide the already registered email ID.
The password should be encrypted and the password field shouldn't be displayed in the admin panel.
Implementation of pagination for all the list view across the application.
Bug fix - Bill payment receipt contains multiple record if the patient has associated with the same doctor multiple times.
Addition of more fields in the prescription statement to make it more specific one.
Addition of more details on payment - such as date of the payment made, amount paid, etc.
Implementation of export button in admin module to export all details to an excel sheet.


Output: 
<img width="1917" height="867" alt="first" src="https://github.com/user-attachments/assets/4278f35b-6f39-4c6a-b905-dfe8412e65c9" />
<img width="1901" height="868" alt="second" src="https://github.com/user-attachments/assets/647819d7-aa5a-42f8-8a7b-49ad6a509922" />
<img width="1900" height="872" alt="third" src="https://github.com/user-attachments/assets/04350894-8a27-46f9-be44-97b6a546cc85" />
<img width="1917" height="871" alt="fourth" src="https://github.com/user-attachments/assets/ceee7242-422e-4c8a-8b09-b29f934f4832" />
<img width="1917" height="868" alt="Fifth" src="https://github.com/user-attachments/assets/5cd083a7-b13d-4307-89e9-422e04fa437a" />





#Skill Navigator Console Application

#Overview
The Skill Navigator Application is a comprehensive platform designed to facilitate skill management and batch allocation for candidates and trainers. The application allows candidates to sign up, provide their educational and professional details, and receive recommendations for appropriate training batches based on their certifications. Trainers can sign in, select specific batches, and view enrolled students. The application is built using Java for the console-based logic and uses XAMPP with MySQL for the backend database.

#Features
Candidate Sign-Up & Sign-In: Allows candidates to create accounts, enter personal and professional details, and sign in to access their profiles.
Batch Recommendation: After sign-up, candidates receive recommendations for training batches based on their certifications.
Batch Allocation: Candidates can select a recommended batch, which is then allocated and recorded in the system.
Trainer Sign-In & Batch Management: Trainers can sign in, select batches, and view details of students enrolled in the selected batch.
Database Integration: Utilizes MySQL with XAMPP for database management, including tables for candidates, batches, and trainers.
Technology Stack



Java: Used for application logic and console-based user interface.
MySQL: Backend database for storing candidate, trainer, and batch information.
XAMPP: Local server environment for database management.


#Installation
Clone the Repository:
git clone https://github.com/Hariharan6052003/Skill-Navigator.git


#Set Up the Database:
Import the SQL schema into your MySQL database.
Create the candidates, batch, and trainer tables as defined in the SQL scripts.

Configure Database Connection:Update the DatabaseConnection class in the MainApp.java file with your MySQL credentials.

Run the Application:Compile and run the Java application using your preferred IDE or command line.

#Usage

#For Candidates:
Sign up to create an account.
Complete your profile and receive batch recommendations.
Select a batch to be allocated.

#For Trainers:
Sign in with your credentials.
Select a batch to manage.
View the list of students enrolled in the selected batch.

Teacher Assignment Management System

This Flask project provides a web-based application designed to assist teachers in managing student assignments. It allows teachers to create classes, add students to those classes, and assign assignments to specific classes.
Features

  * Class Management: Teachers can create classes and assign a unique identifier to each class.
  * Student Management: Teachers can add students to specific classes and manage their information, such as name, ID, and contact details.
  * Assignment Creation: Teachers can create assignments and specify details such as the assignment title, description, due date, and associated class.
  * Assignment Submission: Students can submit their assignments online, providing the necessary information and files.
  * Assignment Tracking: Teachers can track the status of assignments, including submitted, pending, and late submissions.
  * Dashboard: A user-friendly dashboard displays an overview of classes, assignments, and submission status, enabling efficient assignment management.

Installation

To run this project locally, please follow the steps below:

Clone this repository to your local machine using the following command:

    bash

    git clone https://github.com/gorthar/odevtakip.git

Navigate to the project directory:

bash

    cd odevtakip

Create a virtual environment:

For Windows:

    python -m venv venv
    venv\Scripts\activate

For macOS/Linux:

bash

    python3 -m venv venv
    source venv/bin/activate

Install the required dependencies:

    pip install -r requirements.txt

Run the Flask application:



    flask run

    Open your web browser and visit http://localhost:5000 to access the application.

Usage

    Create an account as a teacher using the provided registration form.
    Log in with your credentials to access the dashboard.
    Create classes by clicking on the "Create Class" button and entering the required information.
    Add students to classes by navigating to the desired class and selecting "Add Student." Fill in the student's details and save.
    Create assignments by selecting a class from the dashboard, then clicking on the "Create Assignment" button. Fill in the assignment details and save.
    Students can access the assignment through their accounts and submit their work accordingly.
    Teachers can track assignment submissions, review and grade the assignments as necessary.



License

This project is licensed under the MIT License.
Acknowledgements

This project was written during a period when COVID-19 was widespread, aiming to facilitate teachers in managing student assignments remotely.

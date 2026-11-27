# KLH-FED-2026-StudentProjectAllocationSystem

## 1. Project Title
**Student Project Allocation System**

A web application for listing project topics, collecting student preferences, allocating guides and displaying project assignments.

## 2. Team Members
- Ashwanth – 2620030405
- Viloch – 2620030127
- Eshanth – 2620030131

## 3. Supervisor
Mrs. Surekha

## 4. Abstract

The Student Project Allocation System is a frontend web application that simplifies the allocation of academic projects in a department. When allocation is done manually, it often leads to confusion, duplicate allocations and delays. In this system, faculty members can list project topics with guide details and available slots, while students can view the available topics and submit their preferences in order of priority.

The system automatically allocates projects and guides to students based on their preferences and available slots, ensuring that no topic exceeds its allocation limit.

The application is developed using HTML for page structure, CSS for styling and layout, and JavaScript for handling application functionality, preference processing and allocation logic. Browser LocalStorage is used to store sample data and allocation results.

It provides separate interfaces for faculty and students to manage project topics, submit preferences and view final allocations. The main purpose of this project is to make project allocation faster, more organized and transparent.

## 5. Objectives

- To maintain a list of project topics with guide details in an organized manner.
- To allow students to view available topics and submit their preferences online.
- To allocate projects and guides to students based on their preferences.
- To ensure that no topic or guide is allocated beyond the available slots.
- To display project assignments clearly to students and faculty.
- To provide separate web interfaces for faculty and students.
- To reduce errors, duplicate allocations and delays caused by manual allocation.
- To apply HTML, CSS and JavaScript to a real-world academic problem.

## 6. Features

- Separate login interfaces for Faculty and Students.
- Faculty can add, update and remove project topics.
- Each topic includes its title, description, guide name and available slots.
- Students can view all available project topics in a table.
- Students can submit project preferences in order of priority.
- Automatic allocation of projects and guides based on preferences and availability.
- Prevention of duplicate allocations and over-allocation of slots.
- Display of final project assignments for each student.
- Faculty can view the list of students allocated under them.
- Data storage using browser LocalStorage.
- Simple and responsive user interface.

## 7. Modules

### Faculty Module
- Log in through the faculty login interface.
- Add, update or remove project topics using forms.
- Set the number of available slots for each topic.
- View student preferences.
- View the list of students allocated under them.

### Student Module
- Log in through the student login interface.
- View the list of available project topics and guides.
- Submit project preferences in order of priority.
- View the allocated project and guide.

### Allocation Module
- Reads student preferences one by one.
- Checks whether the preferred topic has available slots.
- Allocates the first available preferred topic and its guide to the student.
- Moves to the next preference if a topic is already full.
- Updates the remaining slots after each allocation.
- Prevents duplicate allocations.

### Display Module
- Displays all project topics with guide details and remaining slots.
- Displays the final project assignments for all students.
- Displays allocation details for a particular student or guide.
- Updates the displayed information dynamically using JavaScript.

## 8. Concepts Used

### HTML
- Page structure using headings, tables, lists and forms.
- Login interfaces for faculty and students.
- Forms for adding topics and submitting preferences.
- Tables for displaying topics and allocation results.
- Dropdown menus for selecting project preferences.

### CSS
- Styling of pages, forms, tables and buttons.
- Separate colour themes for faculty and student pages.
- Flexbox and Grid layouts.
- Responsive design for different screen sizes.
- Hover effects, transitions and animations.

### JavaScript
- Variables, data types and operators.
- Functions and event handling.
- Conditional statements and loops.
- Arrays and objects for storing student, faculty and project information.
- Array methods for filtering, sorting and processing preferences.
- DOM manipulation for dynamically updating webpage content.
- Form validation and event listeners.
- LocalStorage for saving and retrieving application data.
- Functions for project allocation and slot management.
- Exception handling and input validation.

## 9. Technologies Used

- HTML5
- CSS3
- JavaScript
- Visual Studio Code
- Git
- GitHub
- Web Browser
- Browser LocalStorage

## 10. Working Principle

1. Faculty members log in and add project topics with guide names and available slots.
2. Students log in and view the list of available project topics.
3. Students submit their project preferences in order of priority using a form.
4. JavaScript processes each student's preferences.
5. The system checks whether the preferred topic has an available slot.
6. If a slot is available, the project and its guide are allocated to the student.
7. If the topic is full, the system checks the student's next preference.
8. The remaining slots are updated after every allocation.
9. The allocation results are stored using LocalStorage.
10. The final project assignments are displayed on the student and faculty dashboards.

## 11. Setup Instructions

1. Install Visual Studio Code.
2. Install the Live Server extension in Visual Studio Code.
3. Install Git for version control.
4. Clone the project repository from GitHub.
5. Open the project folder in Visual Studio Code.
6. Check the HTML, CSS and JavaScript files.
7. Right-click the main HTML file and select **Open with Live Server**.
8. The application will open in the default web browser.

## 12. Execution Instructions

1. Open the project folder in Visual Studio Code.
2. Start the application using Live Server.
3. Open the application in a web browser.
4. Choose Faculty Login or Student Login on the home page.

**Faculty:**
- Add project topics.
- Set available slots.
- View student preferences.
- View allocated students.

**Student:**
- View available project topics.
- Submit project preferences.
- View the allocated project and guide.

5. Run the automatic allocation process.
6. View the final allocation results.
7. Log out to close the session.

## 13. Data

Sample data is used for testing and demonstrating the Student Project Allocation System.

Sample data includes:
- Student IDs and names.
- Faculty names.
- Project topics and descriptions.
- Available slots.
- Student preferences.
- Final project allocation details.

LocalStorage is used to maintain sample application data in the browser.

No sensitive or personal student information is used in the sample data.

## 14. Results

The application successfully displays project topics, collects student preferences and allocates projects and guides based on availability without exceeding the specified slot limits.

Sample outputs and screenshots demonstrate:
- Faculty login page.
- Student login page.
- Faculty dashboard.
- Student dashboard.
- Project topic listing.
- Student preference submission form.
- Final project allocation results.

## 15. Documentation

Project documentation includes:
- Project requirements.
- Module descriptions.
- Page layouts and wireframes.
- Flowcharts.
- Diagrams.
- Algorithms.
- System design materials.

## 16. Reports

Project reports include:
- Project review documents.
- Project presentation.
- Final project report.
- Implementation and testing reports.

## 17. Current Phase Status

The project is currently in the development phase.

The project requirements, page design and documentation have been prepared. The frontend implementation, JavaScript functionality, testing and further improvements will be developed progressively throughout the project phases.

## 18. Version Control and Collaboration

Git and GitHub are used for version control and team collaboration.

Each team member contributes using their own GitHub account so that individual contributions can be verified through the Git commit history.

The project repository will be maintained throughout the project duration and will remain accessible until the final project evaluation.

## 19. Future Enhancements

- Integrate a backend using Java or other backend technologies.
- Store application data in a database such as MySQL.
- Add allocation based on student CGPA or merit.
- Send email or SMS notifications when projects are allocated.
- Add an admin module to manage faculty and students.
- Allow students to form teams and apply for projects as a group.
- Generate downloadable allocation reports.
- Implement secure authentication.
- Perform further testing and improvements.

## 20. Project Status

**Status: Development in Progress**

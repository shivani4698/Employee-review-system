# Employee Review System using Node.js

## Table of Contents
1. [Description](#description)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Dependencies](#dependencies)
6. [Contributing](#contributing)
7. [License](#license)

## Description
This Employee Review System is a Node.js-based application designed to streamline the employee performance review process within an organization. It allows managers to efficiently evaluate and provide feedback to their team members.

## Features
- User authentication for managers and employees.
- Employee profile management.
- Creation and management of review cycles.
- Reviewer assignment for each employee.
- Review form generation with customizable criteria.
- Submission and tracking of employee reviews.
- Reporting and analytics on employee performance.
- Notifications and reminders for pending reviews.

## Installation
To set up the Employee Review System locally, follow these steps:
1. Clone this repository to your local machine:git clone https://github.com/yourusername/employee-review-system.git2. Navigate to the project directory:cd employee-review-system3. Install the project dependencies:npm install4. Configure your database connection in `config.js`.
5. Run the application:npm start6. Access the application in your web browser at `http://localhost:3000`.

## Usage
1. *Manager Registration*: Managers can create accounts using their email addresses.
2. *Employee Management*: Managers can add employees to the system and assign reviewers.
3. *Review Cycles*: Managers can set up review cycles, defining start and end dates.
4. *Review Forms*: Managers can create customized review forms with criteria specific to their organization.
5. *Employee Reviews*: Employees can access their review forms, fill them out, and submit them.
6. *Review Completion*: Managers can review and provide feedback to employees through the system.
7. *Analytics*: Managers can access performance analytics and reports.

## Dependencies
- Express.js
- MongoDB (or your preferred database)
- Passport.js for authentication
- EJS for templating
- Chart.js for analytics charts

## Contributing
Contributions to this project are welcome. To contribute:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push the branch to your fork.
5. Create a pull request.

## License
This project is licensed under the MIT License.

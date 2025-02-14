# Ar-Riaayah-Academy
Ar-Ria'ayah Academy – Bridging the Gap Between Faith and Future.
Welcome to the Ar-Ria'ayah Academy project! This is a modern, interactive online learning platform inspired by platforms like Coursera. The platform is built using React.js and aims to provide a seamless learning experience for muslim students worldwide.

Project Overview
Ar-Ria'ayah Academy is an online learning platform that offers courses in various Islamic fields. The platform allows users to:

Browse and enroll in courses.

Watch video lectures and complete quizzes.

Track their progress and achievements.

Interact with instructors and other students.

The project is built with React.js for the front end and uses modern web development practices to ensure scalability, performance, and maintainability.

Features
User Authentication: Sign up, log in, and manage user profiles, managed by admin

Course Catalog: Browse and search for courses by category, difficulty, or instructor.

Course Enrollment: Enroll in courses and access course materials.

Progress Tracking: Track progress through courses and quizzes.

Responsive Design: Fully responsive and accessible on all devices.

Admin Dashboard: Manage courses, users, and content (for admins and instructors).

Technologies Used
Front End: React.js, NextJs, Typescript, Zustand (for state management), Axios (for API calls), Tailwindcss (for styling).

Back End: Node.js, Express, MongoDB.

Testing: Jest, React Testing Library.

Version Control: Git, GitHub.

CI/CD: GitHub Actions (for automated testing and deployment).

Other Tools: ESLint, Prettier, Husky (for code quality).

Getting Started
Follow these steps to set up the project locally on your machine.

Prerequisites
Node.js (v16 or higher)

npm (v8 or higher)

Git

Installation
Clone the Repository:

bash
Copy
git clone https://github.com/AjokeCode/ar-riayah-academy.git
cd ar-riayah-academy
Install Dependencies:

bash
Copy
npm install
Set Up Environment Variables:
Create a .env file in the root directory and add the following variables:

env
Copy
REACT_APP_API_URL=http://localhost:5000
REACT_APP_GOOGLE_CLIENT_ID=your-google-client-id
Start the Development Server:

On command Prompt
npm run dev
The app will be running at http://localhost:3000.


Running the Project
Development Mode:


Production Build
npm run build
Running Tests:

bash
Copy
npm test
Contributing
We welcome contributions from the community! Please follow these guidelines to contribute to the project.

Git Workflow
Fork the Repository:

Fork the repository to your GitHub account.

Clone Your Fork:

bash
Copy
git clone https://github.com/your-username/ar-riayah-academy.git
Create a Feature Branch:

bash
Copy
git checkout -b feature/your-feature-name
Commit Your Changes:

Write clear and concise commit messages.

Use the format: type(scope): description (e.g., feat(auth): add login functionality).

Push Your Changes:

bash
Copy
git push origin feature/your-feature-name
Create a Pull Request:

Go to GitHub and create a PR from your branch to develop.

Add a description of your changes and link any related issues.

Code Review Process
All PRs will be reviewed by the maintainers.

Ensure your code follows the project's coding standards.

Address any feedback before the PR is merged.

Deployment
The project is deployed using GitHub Actions and hosted on Netlify (or any other platform of your choice). To deploy:

Push changes to the main branch.

GitHub Actions will automatically build and deploy the app.

License
This project is licensed under the MIT License. See the LICENSE file for details.

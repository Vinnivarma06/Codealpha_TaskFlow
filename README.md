ProjectFlow - Collaborative Project Management
Overview
ProjectFlow is a web-based collaborative project management application designed to streamline task management and team collaboration. It features a user-friendly interface built with HTML, Tailwind CSS, and vanilla JavaScript, allowing users to manage projects, assign tasks, track progress, and communicate effectively.
Features

User Authentication: Secure login with predefined user credentials for demo purposes.
Dashboard: Displays an overview of active projects, completed tasks, and pending tasks.
Project Management: Create, view, and manage multiple projects with detailed descriptions and team assignments.
Kanban Board: Organize tasks into "To Do," "In Progress," "Review," and "Done" columns for efficient workflow tracking.
Task Management: Create, update, and delete tasks with customizable fields like priority, assignee, due date, and status.
Real-Time Notifications: Simulated real-time updates for task assignments, comments, and deadlines.
Team Collaboration: Invite team members to projects and add comments to tasks for seamless communication.
Responsive Design: Fully responsive UI optimized for desktop and mobile devices.

Demo Credentials
For testing purposes, the application includes predefined user accounts:

Username: Select any user from the login dropdown (e.g., Indrarani Sharma, Amulya Patel, Shashank Kumar, Rahul Gupta, Sukumar Singh)
Password: password123

Installation

Clone or Download: Download the project files or clone the repository to your local machine.
Serve the Application: Since this is a static web application, you can serve it using any web server. For example:
Using Python: python -m http.server 8000
Using Node.js: Use a package like http-server (npx http-server)


Access the Application: Open your browser and navigate to http://localhost:8000 (or the appropriate port).

Dependencies

Tailwind CSS: Included via CDN for styling.
Font Awesome: Included via CDN for icons.
No additional backend or database setup is required, as the application uses in-memory data for demo purposes.

Usage

Login: Select a username from the dropdown and enter the password (password123).
Navigate: Use the top navigation bar to switch between the Dashboard and Projects views.
Manage Projects: Create new projects, view existing ones, or open a project to access its Kanban board.
Manage Tasks: Add, update, or delete tasks within a project's Kanban board. Drag tasks between columns to update their status (drag-and-drop functionality would require additional implementation).
Collaborate: Invite team members and add comments to tasks for discussion.
Notifications: View notifications by clicking the bell icon or see toast messages for real-time updates.

Project Structure

index.html: Main HTML file containing the structure, styles, and JavaScript logic.
CSS: Embedded within <style> tags, using Tailwind CSS for responsive design and custom animations.
JavaScript: Embedded within <script> tags, handling all application logic, including authentication, navigation, and task management.

Limitations

Demo Mode: The application uses in-memory data (no persistent storage). Changes are not saved after a page refresh.
Drag-and-Drop: The Kanban board does not currently support drag-and-drop task movement (can be implemented with additional JavaScript).
Backend: No real backend integration; all data is hardcoded for demo purposes.
Security: The login system is simplified for demonstration and not suitable for production use.

Future Improvements

Integrate a backend (e.g., Node.js, Django) with a database for persistent storage.
Implement drag-and-drop functionality for the Kanban board using libraries like Dragula or native HTML5 APIs.
Add real-time collaboration features using WebSockets.
Enhance security with proper authentication and authorization mechanisms.
Expand user roles and permissions for more granular access control.

Contributing
Contributions are welcome! To contribute:

Fork the repository.
Create a new branch for your feature or bug fix.
Submit a pull request with a detailed description of your changes.

License
This project is licensed under the MIT License.

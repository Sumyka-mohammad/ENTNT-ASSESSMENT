Navigation Menu

Code
Issues
Pull requests
The objective of this assignment is to develop a React-based Calendar Application that enables us to efficiently track communication with companies, ensuring follow-ups are timely and consistent.


package-lock.json

package.json

postcss.config.js

tailwind.config.js

 
Calendar Application for Communication Tracking
This Calendar Application helps companies track and manage communication with other organizations. It allows administrators to configure communication parameters, and users can visualize, manage, and log interactions efficiently. The application is built with React and deployed on Netlify.

Features
Admin Module
Company Management: Add, edit, and delete companies with details like name, location, LinkedIn profile, emails, phone numbers, comments, and communication periodicity.
Communication Method Management: Define available communication methods with attributes like name, description, sequence, and mandatory flag.
User Module
Dashboard:
View a grid of companies with columns for company name, last five communications, and next scheduled communication.
Color-coded highlights for overdue (red) and due (yellow) communications.
Hover tooltips to display notes for completed communications.
Communication Action: Log new communications, select communication type, date, and add notes.
Notifications: Display overdue and today’s communications in separate grids with a badge showing counts.
Calendar View: Visualize past and upcoming communications interactively.
Reporting and Analytics Module
Communication frequency report.
Engagement effectiveness dashboard.
Overdue communication trends.
Downloadable reports in PDF or CSV.
Real-time activity log.
Setup Instructions
Prerequisites
Node.js installed on your system.
A code editor like VS Code.
Steps to Run Locally
Clone the repository:

git clone <repository-url>
cd <repository-directory>
Install dependencies:

npm install
Start the development server:

npm start
Open the application in your browser at http://localhost:3000.

Deployment Instructions
This application is deployed on Netlify. To deploy your own version:

Create a Netlify account and link it to your GitHub repository.
Configure the build settings:
Build Command: npm run build
Publish Directory: dist
Deploy the application.
The application will be available at your Netlify-provided URL.

Application Functionality
Admin Features:
Manage companies and communication methods.
User Features:
View and log communications.
Receive notifications for due and overdue tasks.
Use a calendar to track communication schedules.
Analytics Module:
Generate and download reports.
View activity trends and engagement metrics.
Known Limitations
Customization: Limited customization of communication methods.
Offline Mode: Application requires an active internet connection.
Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes.

License
This project is licensed under the MIT License.

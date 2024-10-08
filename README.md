ReachInbox Application
This project is built using Create React App, providing a solid foundation for developing React applications.

How to Get Started
To get started with this project, follow these steps:

Navigate to the Project Directory:

bash
Copy code
cd reachinbox
Install Dependencies:

bash
Copy code
npm install
Start the Application:

bash
Copy code
npm run start
This will launch the app in development mode. Open http://localhost:3000 in your browser to view it. The page will automatically reload if you make any changes to the code, and any lint errors will be displayed in the console.

Application Screenshots
Login Page

Landing Page

After Pressing 'd' or 'D'

After Pressing 'r' or 'R'

All Inboxes

Technologies Used (Frontend)
TypeScript
React
Tailwind CSS
Application Features
User Authentication: Secure login for users.
Fetch Emails: Retrieve emails from the inbox.
Send Emails: Compose and send emails directly from the app.
Delete Emails: Remove unwanted emails from the inbox.
API Endpoints
Retrieve All Emails
http

GET {{baseurl}}/onebox/list
Retrieve Emails from a Specific Thread
http

GET {{baseurl}}/onebox/messages/:thread_id
Send an Email in Response to a Thread
http

POST {{baseurl}}/onebox/reply/:thread_id
Delete an Email
http

DELETE {{baseurl}}/onebox/messages/:thread_id
Deployment
This application is live and can be accessed at: ReachInbox on Netlify.

Available Scripts
Run Tests
bash

npm test
Launches the test runner in interactive watch mode.

Build for Production
bash

npm run build
Generates a production-ready build of the application in the build folder. The build is optimized for performance, and the output files are minified with hash filenames, ready for deployment.

Eject the Project
bash

npm run eject
Warning: Ejecting is a one-way operation. Once you run this command, you cannot revert back to the standard setup. This command will copy all the configuration files and dependencies used by Create React App into your project directory, giving you full control over the project setup.
 

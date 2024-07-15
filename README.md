Customer Transactions Visualization
This project visualizes customer transactions and offers two ways to fetch the data: from a local api.js file or from an API endpoint provided by the backend.

Getting Started
Prerequisites
Node.js
npm (Node Package Manager)


Installation
Clone the repository:
git clone https://github.com/ahmedosama33/route-task-task.git
cd route-task-task


Install dependencies for the frontend:
cd frontend
npm install


Install dependencies for the backend:
cd ../backend
npm install



Running the Application

Frontend
Navigate to the frontend directory:
cd frontend
Start the frontend server:
npm start


Backend
Navigate to the backend directory:
cd backend

Start the backend server:
node server.js


Usage
The frontend application can toggle between using local data from api.js and data fetched from the backend API endpoint (http://localhost:5500/api/data). Use the "Toggle Data Source" button to switch between the two data sources.


Scripts
Frontend
start: Starts the development server.
build: Builds the app for production.
test: Runs the test suite.
predeploy: Runs the build script before deployment.
deploy: Deploys the app to GitHub Pages.
eject: Ejects the create-react-app configuration.



"scripts": {
  "start": "react-scripts start",
  "build": "react-scripts build",
  "test": "react-scripts test",
  "predeploy": "npm run build",
  "deploy": "gh-pages -d build --repo=https://github.com/ahmedosama33/route-task-task",
  "eject": "react-scripts eject"
}


Backend
test: Echoes an error message.


"scripts": {
  "test": "echo \"Error: no test specified\" && exit 1"
}


Project Structure
.
├── frontend
│   ├── public
│   ├── src
│   │   ├── App.css
│   │   ├── App.js
│   │   ├── api.js
│   │   └── index.js
│   ├── package.json
│   └── README.md
└── backend
    ├── server.js
    ├── data
    │   └── data.json
    └── package.json


Data Sources
Local Data: The local data is stored in api.js in the frontend/src directory.
API Data: The backend provides an API endpoint (http://localhost:5500/api/data) to fetch the data.


Author
Ahmed Osama


License
This project is licensed under the MIT License - see the LICENSE file for details.
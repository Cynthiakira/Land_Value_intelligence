Land Value Intelligence
A web-based land value mapping project developed as part of the GeoRAD Academy learning experience.

Project Overview
The Land Value Intelligence project presents selected locations within the Alimosho/Ipaja axis of Lagos State, Nigeria, on an interactive map. The website provides a simple interface where users can search for locations, select a town, and view its available land value information.
The project combines data preparation, JavaScript development, geospatial visualization, and local web hosting to display the final result in a browser.

Tools and Technologies
Google Colab – Used during the data preparation and analysis stage.
Git – Used to manage and bring the project components together.
Visual Studio Code (VS Code) – Used to organize the project files and run the application.
Python – Used during the data-processing stage, where applicable.
JavaScript – Used to manage the website's functionality and interaction with the data.
HTML and CSS – Used to structure and style the website.
JSON – Used to store the Land Intelligence data accessed by the application.
Leaflet – Used for the interactive map interface.
Esri map tiles – Used as the background map shown in the application.
Google Chrome – Used to open and test the running website.
Project Folder Structure

The project was organized in VS Code as follows:
mentorship-starters/
└── land-intelligence/
    ├── data/
    │   └── land-intelligence.json
    ├── notebooks/
    ├── app.js
    ├── index.html
    ├── README.md
    └── styles.css

The data folder contains the JSON dataset used by the application. The notebooks folder holds the project's notebook-related materials, while the HTML, CSS, and JavaScript files provide the website interface and functionality.

Steps Followed

Step 1: Data Preparation in Google Colab
We started by working with the project data and code in Google Colab. We prepared the information needed for the Land Value Intelligence application and organized the relevant outputs for use in the website.

Step 2: Organizing the Project Components
We brought the relevant project components together and organized the files needed for the application. Git was used in managing the project components, while the data and website files were arranged in the project folder.

Step 3: Opening the Project in VS Code
We opened the land-intelligence folder in Visual Studio Code. From the project explorer, we accessed the data folder, notebook folder, JavaScript file, HTML file, CSS file, and README.
This allowed us to manage the website code and its supporting data within one project workspace.

Step 4: Connecting the Website to the Dataset
In app.js, we specified the location of the JSON data file:
const DATA_URL = "../data/land-intelligence.json";
This tells the application where to request the dataset. The JavaScript code uses the data to support the map and location information displayed on the website.

Step 5: Running the Application in VS Code
We started the local development server from the VS Code environment. The terminal displayed the server activity and confirmed successful HTTP requests for the website files.
The terminal output showed successful responses for resources including:
The website page
styles.css
app.js
data/land-intelligence.json
The HTTP status code 200 shown in the terminal indicates that these requests were successful.

Step 6: Opening the Localhost Link in Google Chrome
After starting the server, we opened the local website address in Google Chrome:
http://localhost:5500/land-intelligence/

This allowed us to view the website as a user would see it in a browser.
The localhost address is for local testing on the computer running the server; it is not a permanent public website link.

Step 7: Viewing the Final Output
The browser displayed the Land Value Intelligence interface, including:
An interactive map showing the selected locations.
A search field for finding a town.
A list of five locations: Aboru, Agbelekale, Ajasa / Amikanle, Oke-Odo, and Abule Egba.
Map markers representing the locations.
Zoom-in and zoom-out controls.
A details section for displaying information about a selected location.
The final output demonstrated how the project data and website code worked together to present location information through an interactive map.

Key Learning Outcomes
Through this project, we gained practical experience in organizing project files, preparing data for a web application, connecting JavaScript to a JSON dataset, running a local development server, and testing an interactive map in a browser.
The process also helped us understand how data preparation, web development, and geospatial visualization can work together to present land-related information in a user-friendly format.

Project Status
The application was run locally in VS Code and its output was viewed in Google Chrome. Publishing it online would require a separate deployment step.

Acknowledgement
This project was developed as part of the GeoRAD Academy learning experience, providing an opportunity to apply data handling, coding, and geospatial visualization skills in a practical project.


##Travel Tracker Project 🌍

#Overview
The Travel Tracker Project is a web application that helps users keep track of the countries they’ve visited. It highlights the selected country on a world map, providing an interactive and visual way to manage travel experiences. Users can search for a country by name and add it to their visited list. The app also calculates the total number of countries visited.

#Features
. 🗺️ Interactive World Map: Highlights visited countries on a dynamic SVG map.
. 🔍 Search Functionality: Search for countries by name and add them to the visited list.
. 📊 Progress Tracking: Displays the total count of visited countries.
. ✨ Clean UI: Responsive and user-friendly design with interactive feedback.

**Technologies Used**
. Frontend: HTML, CSS, JavaScript (including SVG for the map)
. Backend: Node.js, Express.js
. Database: PostgreSQL
. Version Control: Git and GitHub
**Setup Instructions**
Follow these steps to run the Travel Tracker Project on your local machine:

1. Clone the Repository
   ```bash
   git clone https://github.com/Mohammed-Farida23/Travel-Tracker-Project.git
   cd Travel-Tracker-Project

2. Install Dependencies
Make sure you have Node.js installed. Run the following command to install required dependencies:
   ```bash
     npm install
3. Set Up the Database
Ensure PostgreSQL is installed and running on your machine.
Create a database (e.g., travel_tracker) using your PostgreSQL client: sql

CREATE DATABASE travel_tracker;
Run the SQL commands in the provided schema.sql file to set up the required tables:
    ```bash
         psql -d travel_tracker -f schema.sql

4.Configure Environment Variables
Create a .env file in the root directory and add the following:
    ```ini
        DB_HOST=localhost
        DB_PORT=5432
        DB_NAME=travel_tracker
        DB_USER=your_postgres_username
        DB_PASSWORD=your_postgres_password
5. Start the Application
Run the app in development mode using:
    ```bash
      npm start
The app will be live at http://localhost:3000.

Usage
Open the app in your browser at http://localhost:3000.
Search for a country by typing its name.
Click "Add" to add the country to your visited list. The map will highlight the country, and the visited count will update.
Project Structure
graphql

       Travel-Tracker-Project/
        ├── public/             # Static files (CSS, client-side JS, images)
        ├── views/              # EJS templates for rendering pages
        ├── routes/             # App routes (e.g., /add, /delete)
        ├── db/                 # Database connection and queries
        ├── app.js              # Main server file
        ├── package.json        # Node dependencies
        └── schema.sql          # SQL file for database setup
Contributing
Feel free to fork the repository and submit pull requests. Contributions are welcome!🚀

License
This project is licensed under the MIT License.

Contact
If you have any questions or feedback, feel free to contact me:
. 📧 Email: faridamohammed@example.com
. 🌐 GitHub: @Mohammed-Farida23











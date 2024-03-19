AirBnB Clone - MySQL
This project is an AirBnB clone implemented using MySQL as the database management system. It aims to replicate some of the functionalities of the popular accommodation booking platform AirBnB.

Features
User authentication: Users can sign up, log in, and log out securely.
Property management: Users can list their properties for rent, edit property details, and delete properties.
Search and booking: Users can search for properties based on various filters such as location, price, and amenities. They can also make bookings for selected properties.
Messaging: Users can communicate with property owners via a messaging system.
Setup
To set up this project locally, follow these steps:

Clone the repository:

bash
git clone https://github.com/WayneRu95/Airbnb-clone-mysql.git
Install dependencies:

Navigate to the project directory and install the required dependencies:

npm install
Database setup:

Create a MySQL database and import the provided SQL schema file.
Update the database configuration in the config/database.js file with your MySQL credentials.
Environment variables:

Create a .env file in the root directory of the project and set the required environment variables. Example:

makefile

DB_HOST=localhost
DB_USER=root
DB_PASSWORD=password
DB_DATABASE=airbnb_clone
Run the application:

Start the application:

bash

npm start
Access the application:

Access the application in your web browser at http://localhost:3000.

Technologies Used
Node.js
Express.js
MySQL
HTML/CSS
Bootstrap (for styling)
Handlebars (for templating)
Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or create a pull request

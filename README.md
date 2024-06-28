🚖 Taxi Meter Application
Project Overview
The Taxi Meter Application is a comprehensive tool designed to manage taxi operations efficiently. This application allows users to log in, start and end rides, calculate fares based on time and distance, and generate detailed reports. The project is implemented in Python and includes various functionalities for both regular users and administrators.

Features
🔐 User Authentication
Login System: Users can log in using their credentials.
Role-Based Access Control: Only administrators have access to certain functionalities, such as changing fare rates.
💵 Fare Calculation
Real-Time Fare Calculation: The application calculates the fare in real-time, charging different rates when the taxi is idle and when it is moving.
Day and Night Rates: Different fare rates for day and night, with night rates being double the day rates.
🚗 Session Management
Start and End Rides: Users can start and end rides, with the fare being calculated based on the duration and type of ride.
Change User: Allows the taxi driver to change users without closing the application.
💼 Fare Adjustment
Admin Feature: Administrators can change the fare rates for both idle and moving states.
📊 Reporting
Generate Reports: The application can generate detailed reports based on ride data, including metrics like rides per month, income per driver, and ride durations.
Visual Representation: Uses libraries like Pandas, Matplotlib, and Seaborn for data visualization to create comprehensive graphs and charts.
Technical Details
📚 Languages and Libraries
Python: The main programming language used for the project.
Pandas: For data manipulation and analysis.
Matplotlib and Seaborn: For generating graphs and visualizations.
Logging: For logging application activity and debugging information.
JSON: For storing user data.
📂 Project Structure
main.py: The entry point of the application.
entrar_con_password.py: Handles user login and password verification.
mostrar_menu.py: Displays the main menu and handles user navigation through the application.
reportes.py: Contains the functionality for generating and displaying reports.
shared.py: A module to share global variables across different parts of the application.
usuarios.json: JSON file for storing user credentials and roles.
Getting Started
🛠️ Prerequisites
Python 3.x
Required Python libraries: Install using pip install -r requirements.txt
📥 Installation
Clone the repository:

sh
Copy code
git clone https://github.com/your-username/taxi-meter-application.git
cd taxi-meter-application
Install dependencies:

sh
Copy code
pip install -r requirements.txt
Run the application:

sh
Copy code
python main.py
Usage
Login: Start the application and log in with your credentials.
Navigate: Use the main menu to start a ride, change the user, or modify fare rates (if you are an admin).
Generate Reports: Access the reporting functionality to view and analyze ride data.

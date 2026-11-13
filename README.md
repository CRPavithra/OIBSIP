# OIBSIP
Python Chat Application

OASIS INFOBYTE Internship  Python Programming | Task 5

Project Objective

To develop a real-time desktop chat application using Python that allows multiple users to communicate through a graphical user interface.

Project Description

A real-time desktop chat application developed using Python Tkinter GUI, Socket Programming, and Multithreading. It enables multiple users to connect to a central server and exchange messages instantly.

Features

- User login with username
- Real-time messaging
- Multiple client connections
- Online users list
- Message timestamps
- Join and leave notifications
- Duplicate username prevention
- Simple and user-friendly graphical interface

Technologies Used

- Python
- Tkinter
- Socket Programming
- Threading
- JSON

Project Structure

Python-Task5-ChatApplication/
│
├── server.py
├── client.py
├── README.md
└── screenshots/

How to Run

1. Clone the repository.

2. Open the project folder in VS Code.

3. Start the server:
   
   "python server.py"

4. Open another terminal.

5. Start a client:
   
   "python client.py"

6. Enter your username.

7. Open additional clients to chat with other users.

Requirements

- Python 3.x
- Tkinter (included with many standard Python installations)

No external Python packages are required.

Screenshots

Screenshots of the application, including the login window, connected users, and message exchange, are available in the "screenshots" folder.

Author

Pavithra CR

OASIS INFOBYTE – Python Programming Internship

 Weather Application

OASIS INFOBYTE – Python Programming Internship | Task 2

A Python-based weather application that retrieves and presents real-time weather information for user-specified locations using the OpenWeatherMap API. The application provides essential weather parameters through a simple and intuitive user interface.

---

📌 Project Overview

The Weather Application is designed to provide users with quick access to current weather conditions by entering a city name. It integrates with the OpenWeatherMap REST API to fetch live weather data and processes the API response to display meaningful weather information.

The project demonstrates practical implementation of Python programming, API integration, HTTP requests, JSON data processing, and exception handling.

✨ Key Features

- City-Based Search: Retrieve weather information by entering a city name.
- Real-Time Weather Data: Fetch current weather conditions through API integration.
- Temperature Monitoring: Display temperature in Celsius.
- Weather Description: Show weather conditions such as clear sky, clouds, and rain.
- Humidity Information: Display the current atmospheric humidity percentage.
- Wind Speed: Retrieve and display wind speed details.
- Error Handling: Manage invalid city names, network failures, and API errors.
- User-Friendly Interface: Provide a simple and accessible user experience.

🛠️ Technology Stack

Technology| Purpose
Python| Core application development
Requests| HTTP requests and API communication
OpenWeatherMap API| Real-time weather data
JSON| Processing API responses

📂 Project Structure

Python-Task2-WeatherApp/
│
├── weather.py
├── requirements.txt
├── README.md
└── screenshots/
    └── weather-app.png

⚙️ Installation and Execution

1. Clone the Repository

git clone YOUR_REPOSITORY_URL

2. Navigate to the Project Directory

cd Python-Task2-WeatherApp

3. Install Dependencies

pip install -r requirements.txt

4. Configure API Key

- Register at "OpenWeatherMap" (https://openweathermap.org/api).
- Generate an API key.
- Configure the key using an environment variable.

Example:

import os

API_KEY = os.getenv("OPENWEATHER_API_KEY")

Set the environment variable before running the application. Never commit API keys or other credentials to GitHub.

5. Run the Application

python weather.py

📊 Weather Parameters

The application retrieves and displays the following information:

Parameter| Description
City| Selected city name
Temperature| Current temperature in °C
Weather| Current weather condition
Description| Detailed weather description
Humidity| Relative humidity (%)
Wind Speed| Wind speed (m/s)

🔗 API Reference

OpenWeatherMap – Current Weather Data API

"https://openweathermap.org/current" (https://openweathermap.org/current)

🎯 Learning Outcomes

Through this project, I gained practical experience in:

- Python application development.
- Integrating third-party REST APIs.
- Sending HTTP requests using the Requests library.
- Extracting and processing JSON responses.
- Implementing exception handling and error management.
- Managing API credentials securely.

👩‍💻 Internship Details

Organization: OASIS INFOBYTE
Internship Domain: Python Programming
Task Number: Task 2
Project: Weather Application

👤 Author

CR Pavithra

Python Programming | Artificial Intelligence & Machine Learning



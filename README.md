<<<<<<< HEAD
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
=======
AI-Powered Voice Assistant

Intelligent Voice Interaction System | Task 1

An interactive, Python-based voice assistant that enables hands-free human-computer interaction through speech recognition and voice synthesis. The application captures spoken commands, interprets user instructions, executes supported operations, and delivers audio responses.

---

Overview

The AI-Powered Voice Assistant is developed to simplify computer interaction through voice-based communication. It integrates speech recognition and text-to-speech technologies to establish an interactive communication system between users and computers.

The application follows a modular architecture that separates voice input processing, command execution, configuration management, and audio response generation.

Core Features

- Speech Recognition: Captures voice input through a microphone and converts speech into text.
- Voice Response Generation: Converts text responses into natural speech using a text-to-speech engine.
- Command Interpretation: Processes recognized instructions and identifies supported operations.
- Automated Task Execution: Performs predefined actions based on user commands.
- Interactive Communication: Supports continuous voice-based interaction.
- Error Management: Handles speech recognition failures and invalid inputs.
- Modular Design: Organizes application components into separate Python modules.

Technology Stack

Component| Technology
Programming Language| Python
Speech Recognition| SpeechRecognition
Audio Input| PyAudio
Speech Synthesis| pyttsx3
Development Environment| Visual Studio Code
Version Control| Git & GitHub

System Architecture

       User Voice Input
              |
              v
       Microphone Input
              |
              v
       Speech Recognition
              |
              v
       Command Processing
              |
              v
       Command Execution
              |
              v
       Response Generation
              |
              v
       Text-to-Speech Engine
              |
              v
       Audio Response

Project Structure

Python-Task1-VoiceAssistant/
│
├── assistant.py       # Main application entry point
├── commands.py        # Voice command processing
├── config.py          # Application configuration
├── requirements.txt   # Project dependencies
├── README.md          # Project documentation
│
└── screenshots/       # Application screenshots

Installation & Execution

Prerequisites

- Python 3.13 or a compatible version
- Working microphone
- Internet connection for online speech recognition
>>>>>>> 830addc (AI Powered Voice Assistant)

1. Clone the Repository

git clone YOUR_REPOSITORY_URL

2. Navigate to the Project Directory

<<<<<<< HEAD
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


=======
cd Python-Task1-VoiceAssistant

3. Create a Virtual Environment

python -m venv venv

4. Activate the Environment

Windows:

venv\Scripts\activate

5. Install Dependencies

pip install -r requirements.txt

6. Launch the Application

python assistant.py

Implementation Highlights

- Microphone-based audio input acquisition.
- Speech-to-text conversion for interpreting spoken instructions.
- Conditional command processing and execution.
- Audio response generation using speech synthesis.
- Modular separation of application responsibilities.
- Exception handling for reliable interaction.

Learning Outcomes

This project provided practical exposure to:

- Python-based application development.
- Speech recognition and audio processing.
- Text-to-speech integration.
- Voice-controlled automation.
- Modular software architecture.
- Debugging and exception handling.
- Working with external Python libraries.

Future Enhancements

- Integration of advanced conversational AI.
- Context-aware voice interactions.
- Expanded system automation capabilities.
- Improved speech recognition accuracy.
- Graphical user interface integration.

Project Information

Attribute| Details
Organization| OASIS INFOBYTE
Internship Domain| Python Programming
Project| AI-Powered Voice Assistant
Task Number| Task 1
Language| Python

Author

Pavithra CR

Artificial Intelligence and Machine Learning

---

Developed as part of the OASIS INFOBYTE Python Programming Internship.
>>>>>>> 830addc (AI Powered Voice Assistant)

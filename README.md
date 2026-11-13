Chat Application 
OASIS INFOBYTE – Python Programming Internship | Task 5

A real-time desktop-based messaging application developed using Python, Tkinter GUI, socket programming, and multithreading. The system enables multiple users to connect to a centralized server and exchange messages through an interactive graphical interface.

Project Overview

The Real-Time Desktop Chat Application is designed to facilitate communication between multiple users over a network.
It follows a client-server architecture in which the server manages client connections and message distribution, while individual clients provide an interactive interface for sending and receiving messages.
The application uses multithreading to handle multiple client connections and support simultaneous message communication without blocking the graphical user interface.

Key Features

- Real-Time Messaging: Enables instant message exchange between connected users.
- Multi-Client Support: Allows multiple clients to connect to a centralized server.
- Graphical User Interface: Provides an interactive desktop interface using Tkinter.
- Socket-Based Communication: Implements network communication using Python sockets.
- Multithreading: Handles simultaneous client connections and message processing.
- User Identification: Supports username-based client login.
- Online User Tracking: Displays currently connected users.
- Message Timestamps: Displays timestamps alongside chat messages.
- Connection Notifications: Provides notifications when users join or leave the chat.
- Client-Server Architecture: Separates communication management from the user interface.

Technology Stack

Technology| Purpose
Python| Core application development
Tkinter| Graphical user interface
Socket Programming| Network communication
Threading| Concurrent client handling
TCP/IP| Reliable network communication
Git & GitHub| Version control and project management

System Architecture

             CHAT SERVER
                  |
       Client Connection Management
                  |
          Message Distribution
                  |
       -----------------------
       |          |          |
       v          v          v
    Client 1   Client 2   Client 3
       |          |          |
       v          v          v
    Tkinter    Tkinter    Tkinter
       GUI        GUI        GUI

Project Structure

Task3-ChatApplication/
│
├── client.py       # Client-side application
├── server.py       # Server-side communication
├── README.md       # Project documentation
│
└── screenshots/    # Application screenshots

Installation and Execution

Prerequisites

- Python 3.x
- Visual Studio Code or any Python-supported IDE
- Basic understanding of networking concepts

1. Clone the Repository

git clone YOUR_REPOSITORY_URL

2. Navigate to the Project Directory

cd Task3-ChatApplication

3. Start the Server

Open the first terminal and execute:

python server.py

4. Launch the Client

Open another terminal and execute:

python client.py

5. Connect Multiple Clients

- Launch "client.py" in multiple terminals or instances.
- Enter a username when prompted.
- Connect to the running server.
- Start exchanging messages in real time.

Working Methodology

1. The server initializes and listens for incoming client connections.
2. Clients establish connections with the server using TCP sockets.
3. Users enter their usernames to identify themselves.
4. The server manages connected clients using multithreading.
5. Messages sent by one client are distributed to other connected clients.
6. The graphical interface displays incoming messages with timestamps.
7. Join and leave notifications update users about connection changes.

Learning Outcomes

This project provided practical experience in:

- Python network programming.
- Client-server communication architecture.
- TCP socket implementation.
- Concurrent programming using multithreading.
- Desktop GUI development using Tkinter.
- Managing multiple client connections.
- Real-time message broadcasting.
- Network communication and exception handling.

Future Enhancements

- Private one-to-one messaging.
- User authentication and account management.
- Message encryption for secure communication.
- File and media sharing.
- Chat history storage.
- Improved interface with customizable themes.

Project Information

Attribute| Details
Organization| OASIS INFOBYTE
Internship Domain| Python Programming
Task| Task 5
Project Type| Desktop Application
Programming Language| Python
Architecture| Client-Server

Author
CR Pavithra
Artificial Intelligence and Machine Learning
Developed as part of the OASIS INFOBYTE Python Programming Internship.




Weather Application
OASIS INFOBYTE – Python Programming Internship | Task 2

A Python-based weather application that retrieves and presents real-time weather information for user-specified locations using the OpenWeatherMap API. The application provides essential weather parameters through a simple and intuitive user interface.

Project Overview

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

Technology Stack

Technology| Purpose
Python| Core application development
Requests| HTTP requests and API communication
OpenWeatherMap API| Real-time weather data
JSON| Processing API responses

Project Structure

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

Weather Parameters

The application retrieves and displays the following information:

Parameter| Description
City| Selected city name
Temperature| Current temperature in °C
Weather| Current weather condition
Description| Detailed weather description
Humidity| Relative humidity (%)
Wind Speed| Wind speed (m/s)

API Reference

OpenWeatherMap – Current Weather Data API

"https://openweathermap.org/current" (https://openweathermap.org/current)

Learning Outcomes

Through this project, I gained practical experience in:

- Python application development.
- Integrating third-party REST APIs.
- Sending HTTP requests using the Requests library.
- Extracting and processing JSON responses.
- Implementing exception handling and error management.
- Managing API credentials securely.

Internship Details

Organization: OASIS INFOBYTE
Internship Domain: Python Programming
Task Number: Task 2
Project: Weather Application

Author
CR Pavithra
Python Programming | Artificial Intelligence & Machine Learning




AI-Powered Voice Assistant
OASIS INFOBYTE – Python Programming Internship | Task 1

An interactive, Python-based voice assistant that enables hands-free human-computer interaction through speech recognition and voice synthesis. The application captures spoken commands, interprets user instructions, executes supported operations, and delivers audio responses.

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

1. Clone the Repository

git clone YOUR_REPOSITORY_URL

2. Navigate to the Project Directory

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
CR Pavithra

Artificial Intelligence and Machine Learning
Developed as part of the OASIS INFOBYTE Python Programming Internship.

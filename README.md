# FitasticFlexieTimer-application
Application Description
FITasticFlexieTimer is a standalone Python application designed to help users efficiently manage their fitness activities by organizing exercises, tracking workout progress, and providing a structured weekly exercise routine in one centralized system.

The application allows users to:
Create and manage personal user information such as name and weight, which are used for tracking fitness progress.
Follow a structured weekly workout plan with different exercises assigned per day.
Start and control a built-in timer for each selected exercise to ensure proper workout duration.
Monitor progress through a visual progress tracker that updates automatically when exercises are completed.
Set weekly availability by entering preferred free days and exercise times for a more personalized workout experience.
Save and load user data, including progress and availability, using local file storage.
Built with a clean graphical user interface using Tkinter, the system emphasizes simplicity, usability, and accessibility. It operates entirely offline and follows a structured Input → Process → Output model, ensuring reliable performance without relying on external databases or internet connectivity.
Through this application, users can improve their discipline, maintain consistency in workouts, and achieve their fitness goals through a guided and organized system.

OOP Concepts Used
This project demonstrates core Object-Oriented Programming principles:
Encapsulation: User data and exercise states are stored within class attributes.
Abstraction: Methods like run_timer() and save_data() hide internal implementation details.
Polymorphism: Exercise actions are handled dynamically through method calls like mark_completed().
Modularity: The system is structured into logical components such as user data handling, UI, and workout logic.

Technologies Used
Python (core programming language)
Tkinter (GUI framework)
JSON (for data storage and retrieval)

Project Structure
FITasticFlexieTimer/
│
├── main.py
│   # Entry point of the application (runs the program)
│
├── models/
│   └── exercise.py
│   # Contains the Exercise class (data model)
│
├── services/
│   └── storage_service.py
│   # Handles saving and loading JSON data (file handling logic)
│
├── ui/
│   └── app.py
│   # Main GUI application (FITasticFlexieTimer class)
│
├── data/
│   └── fitness_data.json
│   # Stores saved user progress and availability
│
└── README.md

Project documentation 
The FITasticFlexie Timer is implemented in a single Python file (main.py), but it follows a structured modular design. The system separates responsibilities into logical sections such as the data model (Exercise class), application controller (FITasticFlexieTimer class), user interface (Tkinter UI methods), and data persistence (JSON file handling).

This structure improves readability, maintainability, and organization by ensuring that each part of the program has a specific role even within a single file implementation.

How to Run
1.	Requirements: Python 3.x installed
2.	Run the application:
                  python main.py

Notes
Designed for educational purposes
Focuses on Object-Oriented Programming principles
Basic validation and error handling only
Runs fully offline without external dependencies

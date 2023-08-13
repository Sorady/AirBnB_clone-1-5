AirBnB clone project
AirBnB

Welcome to the AirBnB clone project!
Table of Contents
Introduction
Features
Technologies Used
The console
Setup and Usage
Introduction:
Welcome to the Airbnb Clone Project! This application is designed to replicate the core functionalities of the popular accommodation booking platform, Airbnb. The project aims to provide familiar and intuitive functionalities for:

create a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file
create all classes used for AirBnB (User, State, City, Place…) that inherit from BaseModel
create the first abstracted storage engine of the project: File storage.
create all unittests to validate all our classes and storage engine
This README is a guide through the features, technologies used, setup instructions, and more.

Features
Users(class): The following are to be used by the user: - show - () - create - () - destroy - () - update - all - () Console(command interpreter): Manages the objects of User class.

Create a new object (ex: a new User or a new Place)
Retrieve an object from a file, a database etc…
Do operations on objects (count, compute stats, etc…)
Update attributes of an object
Destroy an object
Technologies Used
Frontend: (Nothing yet)
Backend: Python
Database: File Storage.
Version Control: Git, GitHub
Here is the flow of the backend.


The console
The console is a command-line interpreter that allows users to manage and manipulate instances of various classes in an application. The primary purpose of this script is to provide a way to interact with and manipulate objects by executing specific commands. The script operates within a command loop, where users can enter commands to create, retrieve, update, and delete instances of different classes.



Setup and Usage
The command interpreter supports a variety of operations for managing objects within the application. It enables users to interact with the data model in a structured way. Below are the key operations that can be performed using this command interpreter:

Create: Create a new instance of a specified class.
Show: Retrieve and display information about a specific instance based on its class and ID.
Destroy: Delete a specific instance based on its class and ID.
All: Display information about all instances or instances of a specific class.
Update: Update attributes of a specific instance based on its class and ID.
Count: Count the number of instances of a specific class.
Quit/Exit: Terminate the command interpreter.
contributors

Ahmed elsorady ahmedelsorady2015@gmail.com
Beshoy beshoy@gmail.com

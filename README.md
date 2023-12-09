Airbnb Clone - The console


Project Description

```This project aims to build a command-line application (CLI) that serves as the backend for an Airbnb-like platform. This console app will allow users to manage various aspects of the platform, including:```

    Creating and managing user accounts: Users can register, login, and update their information.
    Adding and editing listings: Hosts can create listings for their properties, specifying details like location, amenities, and price.
    Searching and booking accommodations: Guests can search for available listings based on their criteria and book their stays.
    Managing reservations: Hosts and guests can manage their reservations, including checking availability, making payments, and reviewing each other.

This project will utilize Python and leverage object-oriented programming to model different entities like users, listings, reservations, etc. It will also implement a file-based storage system to persist data.
Description of the Command Interpreter

The command interpreter acts as the interface for users to interact with the Airbnb platform. It provides a prompt where users can enter commands to manipulate data. The interpreter parses the commands, identifies the action requested, retrieves or updates the relevant data, and presents the results.

```Here are some key features of the command interpreter:```

    Interactive: Users can repeatedly enter commands and receive feedback.
    Command-based: Each operation is triggered by a specific command.
    Flexible: The interpreter supports various commands for different functionalities.
    Extensible: New commands can be added to expand the app's capabilities.

Starting the Project

Prerequisites:

    Python 3.x installed
    Virtual environment (recommended)

```Steps:```

    Clone the project repository or download the project files.
    Open a terminal in the project directory.
    Create a virtual environment (optional): python3 -m venv venv.
    Activate the virtual environment: source venv/bin/activate (Linux/Mac) or venv\Scripts\activate.bat (Windows).
    Install the required dependencies: pip install -r requirements.txt.
    Run the main script: python3 console.py.

Using the Command Interpreter

Once the command interpreter starts, it will display a prompt. Users can then enter commands to perform various actions. The available commands are listed below:

    create: Creates a new entity (user, listing, reservation).
    show: Displays details of an existing entity.
    update: Modifies attributes of an existing entity.
    destroy: Deletes an existing entity.
    all: Lists all entities of a specific type or all entities in the system.
    count: Counts the number of entities of a specific type.
    help: Displays help information about a specific command or all commands.
    quit: Exits the command interpreter.

```Each command requires specific arguments depending on its functionality. For example, the create command requires additional information like the entity type and its attributes.
Examples```

```Create a new user:```

create user --name "Simon Peter" --email "simonpeter@hotmail.com" --password "password"

```Show the details of a listing:```

show listing --id 12345

Update the price of a listing:

update listing --id 12345 --price 100

```List all users:```

all user

```Get the number of available listings:```

count listing --available

```Exit the command interpreter:```

quit


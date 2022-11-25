Description of the project?

This is the first step towards building your first full web application: the AirBnB clone. The aim of the project is to deploy a replica of the Airbnb Website using my server. The final version of this project will have:

-A command interpreter to manipulate data without a visual interface, like a shell (for development and debugging)
-A website (front-end) with static and dynamic functionalities
-A comprehensive database to manage the backend functionalities
-An API that provides a communication interface between the front and backend of the system.

Resources

-Videos showing examples of how various parts of the project work, listed below:
-HBNB videos
-Holberton Airbnb overview
-The Airbnb Console
-Airbnb ORM
-Airbnb API
-Final product
-Other resource
-cmd module
- packages concept page
- Python packages
- uuid module
- datetime
- unittest module
- args/kwargs
- Python test cheatsheet
- AirBnB website.

Aims & Objectives of this project

This will help to be able to manage the objects of our project:

-Creation of a new object (ex: a new "User" or a new "Place")
-Retrieval of an object from a file storage, a database etc...
-Perform operations on objects (count, compute stats, etc...)
-Update attributes of an object
-Destroy an object

Description of the command interpreter?

Commands	Description
quit	This command quits or exits the console
EOF	This command quits or exits the console interpreter when pressed Ctrl+D
help or help <command>	Displays all commands or Displays instructions for a specific command (Ex: help or help quit).
create <class>	Creates an object of type, saves it to a JSON file, and prints the objects ID (Ex: create BaseModel or BaseModel.create())
show <class> <ID>	Shows string representation of an object (Ex: show BaseModel 1234-1234-1234 or BaseModel.show("1234-1234-1234"))
destroy <class> <ID>	Deletes an objects based on the class name and id (Ex: destroy BaseModel 1234-1234-1234 or BaseModel.destroy("1234-1234-1234")).
all or all <class>	Prints all string representations of all objects or Prints all string representations of all objects of a specific class (Ex: all BaseModel or all or User.all()).
update <class> <id> <attribute name> "<attribute value>"	Updates an object with a certain attribute (new or existing) (Usage: update <class name> <id> <attribute name> "<attribute value>).
<class>.all()	Same as all <class>
<class>.count()	Retrieves the number of objects of a certain class (Usage: <class name>.count(), Example: User.count()).
<class>.show(<ID>)	Same as show <class> <ID>
<class>.destroy(<ID>)	Same as destroy <class> <ID>
<class>.update(<ID>, <attribute name>, <attribute value>	Same as update <class> <ID> <attribute name> <attribute value>
<class>.update(<ID>, <dictionary representation>)	Updates an objects based on a dictionary representation of attribute names and values

Compilation
To start up the interpreter, clone this repository, and run the console file on linux as follows:

Clone this repository: git clone "https://github.com/Dikachis/AirBnB_clone.git"
Access AirBnb directory: cd AirBnB_clone
Run hbnb(interactively): ./console and then press enter command
Run hbnb(non-interactively): echo "<command>" | ./console.py

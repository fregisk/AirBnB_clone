LOGO-PROJECT (1)
This repository is the first part of a big project. We will create a clone of Airbnb, create objects and interact with them

How to start it
git clone i

How to use
We will see the different commands that we can use in our Interpreter

Create
Show
All
Update
Destroy
Interactive mode
In this Interactive mode the console will display a prompt (hbnb), that indicates the user can write and execute a command. You need to run the the file ./console.py. and if you would like to exit, you need to type quit in the prompt.

$ ./console.py
(hbnb) help
Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb)
(hbnb)
(hbnb) quit
$

#### Interactive mode

user@ubuntu::~/AirBnB$ ./console.py (hbn) all [] (hbn)

Now, we are going to start with the command  ***create***
 For this command you can create different classes in different files like these:

* BaseModel ------- (```Class```)
* City ----------------- (```Inherited class from base models```)
* Place ----------------- (```Inherited class from base models```)
* Amenity ----------------- (```Inherited class from base models```)
* State ----------------- (```Inherited class from base models```)
* Review ----------------- (```Inherited class from base models```)


--- ```Public instance attributes``` ---
  * id
  * created
  * updated


#### Non-Interactive mode
In this **Non-Interactive** mode the console will display a prompt (hbnb) but need to be run with a command input piped into its execution so that the command is running as soon as the console starts. In this mode no prompt will appear, and no further input will be expected from the user.
$ echo "help" | ./console.py (hbnb) Documented commands (type help ):
EOF help quit (hbnb) $ $ cat test_help help $ $ cat test_help | ./console.py (hbnb) Documented commands (type help ):
EOF help quit (hbnb) $

✳️ Command ✳️
Command	Usage	Description
quit or EOF		Exits the program
Help	help <command>	Provides a text describing how to use a command.
Created	create <class name>	Creates an object of the class declared by user;
Show	show <class name> <id>	Prints the string representation of an instance based on the class name and id
Updated	update<class name> <id> <attribute name> <attribute value>	Updates an instance based on the class name and id by adding or updating attribute (saves the changes into a JSON file).
all	all <class name>	Prints all string representation of all instances based on the class name.
Destroy	destroy <class name> <id>	Deletes an instance based on the class name and id .
Web static
learn HTML/CSS
create the HTML of your application
create template of each object

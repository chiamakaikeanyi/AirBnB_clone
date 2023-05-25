# AirBnB clone

## Feature

Command Interpreter

## Description

The Command Interpreter is used to manage the application's functionality:

- Create a new object.
- Retrieve an object from a file, database, etc.
- Execute operation on objects. e.g. Count, compute statistics, etc.
- Update object's attributes.
- Destroy an object.

## Usage

To launch the console application in interactive mode simply run:

`console.py`

or to use the non-interactive mode run:

`echo "your-command-goes-here" | ./console.py`

Commands
|   Commands   |           Description              |    Usage      |
| ------------ | ---------------------------------- | ------------- |
| help or ?    | Displays the documented commands   | help          |
|              |                                    |               |
| quit         | Exits the program.                 | quit          |
|              |                                    |               |
| EOF          | Ends the program.Used when files   |               |
|              | are passed into the program.       | N/A           |
|              |                                    |               |
| create       | Creates a new instance of the      | create        |
|              | <class_name>.Creates a Json file   | <class_name>  |
|              | with the object representation. and|               |
|              | prints the id of created object    |               |
|              |                                    |               |
| show         | Prints the string representation of|    show       |
|              | an instance based on the class name| <class_name   |
|              | and id.                            | class_id>     |
|              |                                    |               |
| destroy      | Deletes and instance base on the   | destroy       |
|              | class name and id.                 | <class_name   |
|              |                                    | class_id>     |
|              |                                    |               |
| all          | Prints all string representation of| all or all    |
|              | all instances based or not on the  | <class_name   |
|              |                                    | class_id>     |
|              |                                    |               |
| update       | Updates an instance based on the   | update        |
|              | class name and id by adding or     | <class_name   |
|              | updating attribute                 | class_id key  |
|              |                                    | value>        |

## Tests

To execute the tests, run the command below from the root directory:

`python3 -m unittest discover tests`


Project Description:

The AirBnB clone project aims to develop a simplified version of the popular vacation rental platform, AirBnB. This project involves building a command-line interface (CLI) for managing AirBnB objects such as users, states, cities, places, and more. The project includes creating Python classes representing these objects, implementing serialization and deserialization, and developing a storage engine for managing data persistence.

Command Interpreter Description:

The command interpreter is a command-line interface (CLI) program that allows users to interact with and manage AirBnB objects. It provides a set of commands for creating, reading, updating, and deleting (CRUD) operations on various types of objects.

How to Start the Command Interpreter:

1. Clone the project repository from [GitHub Repository URL].
2. Navigate to the project directory in your terminal or command prompt.

How to Use the Command Interpreter:

Once the command interpreter is started, you can use the following commands to interact with the AirBnB objects:

- `create`: Create a new instance of an AirBnB object.
- `show`: Display details of a specific AirBnB object.
- `update`: Update attributes of an existing AirBnB object.
- `destroy`: Delete an AirBnB object.
- `all`: Show all instances of a specific AirBnB object type or all instances across all object types.
- `quit` or `EOF`: Exit the command interpreter.

Examples:

1. To create a new user:
   ```
   (command prompt)$ create User
   ```

2. To show details of a user with ID `1234`:
   ```
   (command prompt)$ show User 1234
   ```

3. To update the name attribute of a place with ID `5678`:
   ```
   (command prompt)$ update Place 5678 name "New Name"
   ```

4. To delete a state with ID `9876`:
   ```
   (command prompt)$ destroy State 9876
   ```

5. To display all instances of the user object:
   ```
   (command prompt)$ all User
   ```

6. To exit the command interpreter:
   ```
   (command prompt)$ quit
   ```


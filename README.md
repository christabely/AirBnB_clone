# AirBnB Clone Project

![AirBnB Logo](https://www.pngitem.com/pimgs/m/132-1322125_transparent-background-airbnb-logo-hd-png-download.png)

## Project Description

Welcome to the AirBnB Clone Project! This project is the backend portion of our AirBnB clone, complete with a console application powered by Python's `cmd` module. We've designed this application to emulate the functionality of Airbnb, allowing users to interact with a simplified version of the platform through the command line.

Data in the form of Python objects is generated and stored in JSON files, accessible via Python's `json` module.

## Command Interpreter

Our command interpreter replicates the experience of using a Bash shell with a defined set of commands tailored for the AirBnB website's purposes. This interactive interface serves as the frontend for the web app, leveraging Python's object-oriented programming for backend functionality.

Some available commands include:

- `show`: Display information about an object.
- `create`: Create new objects (e.g., User, Place).
- `update`: Modify object attributes.
- `destroy`: Delete an object.
- `count`: Retrieve the number of instances of a class.

These commands allow you to interact with objects, retrieve information, and perform essential operations.

## Getting Started

To run the AirBnB Clone Project on your local Linux machine for development and testing, follow these steps:

### Installation

1. Clone the project repository from GitHub:

   ```
git clone https://github.com/Mzpenelope/AirBnB_clone.git
   ```

2. Navigate to the project directory:

   ```
   cd AirBnB_clone
   ```

### Usage

You can use the command interpreter in two modes: Interactive and Non-interactive.

#### Interactive Mode

In this mode, the console displays the `(hbnb)` prompt, waiting for your input and providing immediate feedback.

```bash
$ ./console.py
(hbnb) help
...
(hbnb) quit
...
```

#### Non-interactive Mode

In this mode, you pipe commands into the console for execution without the need for interactive input.

```bash
$ echo "help" | ./console.py
...
```

#### Command Input Format

Commands and arguments should be separated by spaces. For example:

```bash
(hbnb) create BaseModel
...
```

### Available Commands

Here are some of the commands you can use with the command interpreter:

- `quit` or `EOF`: Exit the program.
- `help`: Display instructions on how to use a command.
- `create`: Create a new instance of a class and save it to the JSON file.
- `show`: Display information about an instance based on class name and ID.
- `destroy`: Delete an instance based on class name and ID.
- `all`: Print string representations of all instances or by class name.
- `update`: Update instance attributes.
- `count`: Retrieve the number of instances of a class.

## Author

This project is maintained by Phillipa and Christabel.

Feel free to explore the AirBnB Clone Project's functionality and experiment with the command interpreter to create, manage, and interact with property listings. Enjoy your virtual Airbnb experience!

# AirBnB Clone - The Console

This project includes a command interpreter to manage the Airbnb clone's data and objects. It allows administrators and other users to manipulate various types of data.

## Managed Objects

The console allows manipulation of the following objects:
- Users
- Places
- States
- Cities
- Amenities
- Reviews

![Airbnb Clone Diagram](https://i.ibb.co/RSzZ5yh/815046647d23428a14ca.png)

## Requirements

### Python Scripts

- **Allowed editors**: vi, vim, emacs
- **Environment**: Ubuntu 14.04 LTS using python3 (version 3.4.3)
- All files should end with a new line
- The first line of all files should be exactly `#!/usr/bin/python3`
- A `README.md` file, at the root of the folder of the project, is mandatory
- Code should follow the PEP 8 style (version 1.7+)
- All files must be executable
- File length will be tested using `wc`
- All modules, classes, and functions should have documentation (use python3 -c 'print(__import__("my_module").__doc__)' etc.)

### Python Unit Tests

- **Allowed editors**: vi, vim, emacs
- All test files should be inside a `tests` folder
- Use the unittest module
- Test files should have the `.py` extension and start with `test_`
- Organize test files in the same structure as the project files
- Execute tests using `python3 -m unittest discover tests` or file by file
- Documentation is required for all modules, classes, and functions

### Installation

Requirements:
- Linux Ubuntu 14.04.3 LTS or higher
- Python 3.7 or higher

### Files

- Console: `HBNHCommand: console.py`
- Models:
  - `Amenity: models/amenity.py`
  - `BaseModel: models/base_model.py`
  - `City: models/city.py`
  - `__init__: models/__init__.py`
  - `Place: models/place.py`
  - `Review: models/review.py`
  - `State: models/state.py`
  - `User: models/user.py`
- Storage:
  - `FileStorage: models/engine/file_storage.py`
  - `__init__: models/engine/__init__.py`

### Running the Command Interpreter

To run the console:

```
bash
$ ./console.py
```

## Examples

Interactive mode:
```
$ ./console.py
(hbnb) help
Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb)
(hbnb) quit
$
```

Non-interactive mode:
```
$ echo "help" | ./console.py
(hbnb)
Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb) 
$
$ cat test_help | ./console.py
(hbnb)
Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb)
$
```

## AUTHOR
Getayawkal Wondimagegnehu <Getayawkal.won@gmail.com>

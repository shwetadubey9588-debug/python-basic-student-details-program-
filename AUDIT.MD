# README Audit

## README Fact-Check Table

| Claim Made in README                                        | True? | Evidence / Correction Made                                                                                          |
| ----------------------------------------------------------- | ----- | ------------------------------------------------------------------------------------------------------------------- |
| Program prints student details                              | Yes   | The program uses `print()` statements to display student information.                                               |
| Program displays the student's name                         | Yes   | The code stores and prints the student's name.                                                                      |
| Program displays the student's roll number                  | Yes   | The code stores and prints the student's roll number.                                                               |
| Program displays the student's marks                        | Yes   | The code stores and prints the student's marks.                                                                     |
| Program accepts student details from the user               | No    | No `input()` function is used. Student details are already defined in the code. Claim deleted.                      |
| Program takes input from the terminal                       | No    | There is no terminal input operation in the program. Claim deleted.                                                 |
| Program can store details of multiple students              | No    | The program contains details for a single student. Claim deleted.                                                   |
| Program uses a Python structure similar to C `struct`       | Yes   | Python data structures can be used to group student information, but Python does not have C-style `struct` syntax.  |
| Program uses external Python libraries                      | No    | No external libraries are imported.                                                                                 |
| Python 3 is required                                        | Yes   | `structstudent.py` is a Python script and can be executed using Python 3.                                           |
| No external dependencies are required                       | Yes   | The program uses only Python's built-in functionality.                                                              |
| Program validates the student's marks                       | No    | There is no condition to check whether marks are within a valid range. Claim deleted.                               |
| Program validates the roll number                           | No    | There is no validation logic for the roll number. Claim deleted.                                                    |
| Program handles invalid input                               | No    | No user input or `try/except` error-handling logic exists. Claim deleted.                                           |
| Program allows the user to edit student details at runtime  | No    | The program does not provide runtime input or editing functionality. Claim deleted.                                 |
| Program prints student information in a readable format     | Yes   | The student details are displayed using formatted `print()` statements.                                             |
| Project contains `structstudent.py`                         | Yes   | `structstudent.py` is the Python source file for the project.                                                       |
| Program is suitable for beginners learning Python           | Yes   | The program demonstrates basic variables/data storage and `print()` statements using simple Python syntax.          |
| A `requirements.txt` file is required                       | No    | No external packages are required, so a dependency file is unnecessary. Installation instruction removed.           |
| NumPy is required                                           | No    | There is no `import numpy` statement and NumPy is not used. Claim deleted.                                          |
| Project uses MIT License                                    | No    | No `LICENSE` file was specified or provided. Licence claim should be removed unless an MIT `LICENSE` file is added. |
| Program can be run using `python structstudent.py`          | Yes   | `structstudent.py` is a standalone Python script that can be executed with Python.                                  |
| Program displays the student's name, roll number, and marks | Yes   | These three student details are the information displayed by the program.                                           |

[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15310797&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.

Answer:

   - Python is a high-level, interpreted programming language
     
 Python key features:
 
   - Easy to Learn and Use: Simple syntax that mimics natural language.
     
   - Interpreted Language: Executes code line by line, which makes debugging easier.
     
   - Versatile and Powerful: Supports various programming paradigms (procedural, object-oriented, functional).
     
   - Extensive Libraries and Frameworks: Access to a wide range of libraries like NumPy, Pandas, Matplotlib, Django, Flask, etc.
     
   - Community Support: Large and active community
Sources:

<a href="https://docs.google.com/presentation/d/1AILPQwnGFt387QS6LgqPxR7DpngEx9GJ/edit#slide=id.p3">python features</a>

2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.

   Answer:

    - Here are the steps to install Python on Windows:

     Download Python:
   
      - Visit the Python Releases for Windows page.
      - Choose the latest version (e.g., Python 3.12.4) compatible with your system architecture (64-bit or ARM64).
      - Download the Windows installer.
        
     Run the Installer:
   
      - Double-click the downloaded installer.
      - Check the box to add Python to PATH during installation (recommended).
      - Click “Install Now.”
        
    Customize Installation (Optional):

      - You can customize the installation by selecting additional features or adjusting settings.
      - For most users, the default options are sufficient.
        
    Verify Installation:

      - Open a Command Prompt or PowerShell window.
      - Type `python --version` and press Enter.
      - You should see the installed Python version (e.g., “Python 3.12.4”).
      - 
   Set Up a Virtual Environment :

      - Install the virtualenv package (if not already installed):
         
        `pip install virtualenv` 
       

        Create a new virtual environment:
        
      - `python -m venv myenv`

   Activate the virtual environment:

    - Command Prompt: `myenv\Scripts\activate`
      
   Source:

    - <a href="https://www.python.org/downloads/windows/">install python </a>
    - <a href="https://kinsta.com/knowledgebase/install-python/">python</a>
   
4. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.

     Answers:

       This program prints Hello, world!
       print('Hello, world!')
     - We use the built-in print() function to display the string “Hello, world!” on the screen.

     Sources:

      - <a href="https://www.programiz.com/python-programming/examples/hello-world">python syntax</a>

5. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.

Answers:

   - Text Type (str): Represents textual data, such as words or sentences.
     
Numeric Types:

   - int: Used for whole numbers (e.g., 5, -10).
     - float: Represents decimal numbers (e.g., 3.14, -0.5).
     - complex: Handles complex numbers (e.g., 2 + 3j).
       
Sequence Types:

   - list: An ordered collection of items (e.g., `[1, 2, 3]`).
   - tuple: Similar to a list but immutable (e.g., `(1, 2, 3)`).
   - range: Represents a sequence of numbers (e.g.,` range(5)`).
     
Mapping Type:

 - dict: Stores key-value pairs (e.g., {`name: "John", "age": 30 `}).

examples :
    
      text_variable = "Hello, world!"
      print(text_variable)
      
      integer_variable = 42
      print(integer_variable)
      
      float_variable = 3.14
       print(float_variable)
       
       boolean_variable = True
       print(boolean_variable)
       
       list_variable = [1, 2, 3]
       print(list_variable)
       
       dictionary_variable = {"name": "Alice", "age": 25}
       print(dictionary_variable)

6. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.

 Answers:
    if (condition):
      - Executes this block if
      - condition is true
    else:
      - Executes this block if
      - condition is false
      
  Example of if else :
  
      x = 3 
     if x == 4: 
      print("Yes") 
    else: 
    print("No")
    
   output = No
  source:
   - <a href="https://www.geeksforgeeks.org/conditional-statements-in-python/">Conditional Statement</a>

7. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.

   Answers:

   -Functions in Python are essential building blocks that allow us to organize and reuse code efficiently. They provide a way to encapsulate a set of instructions, perform specific tasks, and return results
   
   Example:

        def add_numbers(num1, num2):
       return num1 + num2

       result = add_numbers(5, 3)
         print("Sum:", result)
   
 output: 
 
   Sum: 8

Sources:

- < a href="https://www.w3schools.com/python/python_functions.asp">python function</a>

9. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.

  Answer:

   - Lists are just like arrays, declared in other languages. Lists need not be homogeneous always which makes it a most powerful tool in Python.
   - Python Dictionary on the other hand is an unordered collection of data values, used to store data values like a map,

Example:

 - Create a list of numbers:
   
       numbers = [1, 2, 3, 4, 5]

 - Create a dictionary with key-value pairs:
   
       my_dict = {
            'name': 'Alice',
            'age': 30,
           'city': 'Wonderland'
          }

- Accessing elements:
  
       print("First number:", numbers[0])
       print("Age of", my_dict['name'], "is", my_dict['age'])

- Modifying elements:
  
       numbers[2] = 10
      my_dict['city'] = 'New York'

 - Adding elements:
   
       numbers.append(6)
       my_dict['country'] = 'USA'

- Removing elements:
  
      del numbers[1]
      my_dict.pop('age')

- Length of list and dictionary:
  
      print("Number of elements in the list:", len(numbers))
      print("Number of key-value pairs in the dictionary:", len(my_dict))

- Iterating through list and dictionary:
  
      for num in numbers:
       print("Number:", num)

      for key, value in my_dict.items():
      print(f"{key}: {value}")

Source:

-<a href="https://www.geeksforgeeks.org/difference-between-list-and-dictionary-in-python/">lists and dict</a>

10. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.

Answers:

 -Exception handling in Python allows you to gracefully handle errors or exceptional situations that may occur during program execution.

 Try-Except Blocks:
 
   - You use try and except blocks to catch exceptions (errors) that might occur within a specific section of code.
   - The try block contains the code that might raise an exception.
   - The except block specifies what to do if an exception occurs. You can handle different types of exceptions separately.
     
Common Exception Types:

Some common exceptions include:

  - ZeroDivisionError: Raised when dividing by zero.
  - ValueError: Raised when an operation receives an inappropriate value.
  - TypeError: Raised when an operation is performed on an inappropriate data type.
  - FileNotFoundError: Raised when a file is not found.
  - IndexError: Raised when accessing an index that is out of range.
And many more…

Handling Exceptions:
You can catch specific exceptions using except blocks. For example:

 Example:

    -try:
    result = 10 / 0
    expect ZeroDivisionError:
    print("Error: Cannot divide by zero")

Handling Multiple Exceptions:

   -You can handle multiple exceptions in a single try block:

         try:
    # Some code that might raise exceptions
     except (ValueError, TypeError) as e:
      print(f"An error occurred: {e}")

11. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.

Answer:

 - A module in Python is a single file that contains Python code in the form of functions, executable statements, variables, and classes. A module acts as a self-contained unit of code that can be imported and used in other programs or modules.
 - A package, on the other hand, is a collection of modules organized in a directory. Packages allow us to group multiple related modules together under a common namespace, making it easier to organize and structure our code base.

Example:

  - To use a module, you import it using the import statement.
    
Examples:

  - Import the entire module:` import math`
  - Import specific names from a module: `from math import sqrt, pi`
  - Import with an alias:` import math as m`

code :

    import math

    # Example usage
       radius = 5
      area = math.pi * radius**2
     square_root = math.sqrt(25)

    print(f"Area of a circle with radius {radius}: {area:.2f}")
    print(f"Square root of 25: {square_root:.2f}")

  Output:

   - Area of a circle with radius 5: 78.54
   - Square root of 25: 5.00

  Source:

   -<a href="https://www.sitepoint.com/python-modules-packages/">Modules and packages</a>
   
12. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.

Answers:

  - Reading and Writing Lists to a File in Python
The open(file path, mode) is used to open the required file in the desired mode. The open() method supports various modes of which three are of main concern:

 - r:  read (default)Python
 - w: write
 - a: append
 - write(): Insert the string str1 in a single line in the text file.

 - read(): used to read data from the file opened using the open() method.

code :

     -# assign list
         l = ['Geeks','for','Geeks!']
 
    # open file
     with open('gfg.txt', 'w+') as f:
     
    # write elements of list
    for items in l:
        f.write('%s\n' %items)
     
    print("File written successfully")
 
 
      # close the file
         
        f.close()
 another :

    L = ["Geeks\n", "for\n", "Geeks\n"]
 
    # writing to file
    file1 = open('test1/myfile.txt', 'w')
     file1.writelines(L)
     file1.close()

# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].



# Database Interaction with SQLite

import sqlite3
conn = sqlite3.connect('example.db')
cursor = conn.cursor()

  # Execute SQL query
cursor.execute('CREATE TABLE IF NOT EXISTS users (id INTEGER PRIMARY KEY, name TEXT)')

  # Commit changes
conn.commit()

  # Close connection
conn.close()

# Data Types

int_num = 42
float_num = 3.14
string_var = "Hello, Python!"
bool_var = True

# Dictionaries

my_dict = {'name': 'John', 'age': 25, 'city': 'Pythonville'}

#Classes & Objects

class Dog:
    def __init__(self, name):
        self.name = name
def bark(self):
        print("Woof!")
my_dog = Dog("Buddy")
my_dog.bark()

# File Handling

with open("file.txt", "r") as file:
    content = file.read()
with open("new_file.txt", "w") as new_file:
    new_file.write("Hello, Python!")

 # Exception Handling

try:
    result = 10 / 0
except ZeroDivisionError:
    print("Cannot divide by zero!")
finally:
    print("Execution completed.")   

# Dictionary Manipulations

my_dict = {'a': 1, 'b': 2, 'c': 3}

  # Get value with default
value = my_dict.get('d', 0)

   # Dictionary comprehension
squared_dict = {key: value**2 for key, value in my_dict.items()}

    

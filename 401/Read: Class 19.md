# Readings: Automation

1. How can you use regular expressions in Python to search for specific patterns in a string, and what is the primary library to work with them?

- To use regular expressions in Python, import the re module. Define the pattern you want to search for and use functions like re.search() or re.findall() to find matches. The re module is the primary library for working with regular expressions in Python.

2. What is the purpose of the shutil library in Python, and provide an example of a common use case for file or directory management with this library?

- The shutil library in Python provides functions for file and directory operations. A common use case is copying files or directories using shutil.copy() or shutil.copytree(). Other functions like shutil.move(), shutil.rmtree(), and shutil.rename() handle moving, deleting, and renaming files and directories. It simplifies file and directory management tasks in Python.

3. Explain one automation idea from the assigned material and describe how it can be implemented using Python’s regular expressions and shutil libraries.

- You can automate the organization of downloaded files into specific folders based on their file types using Python's regular expressions and shutil libraries. Extract the file extension using regular expressions and move the files to the appropriate folders using shutil.move().

## Things I want to learn more about

Are there any specific file types or patterns that need to be considered for organizing the files?

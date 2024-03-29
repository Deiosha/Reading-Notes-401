# Read: Class 08

1. What is the basic syntax of Python list comprehension, and how does it differ from using a for loop to create a list? Provide an example of a list comprehension that squares the elements in a given list of integers.
my_new_list = [ expression for item in list ]. A for loop in Python is used to iterate through any iterable object. It authorizes you to execute any functions on the items in the iterable, including appending them to a new list.
numbers = [3, 7, 11, 15, 19]
squared_numbers = []
for i in range(len(numbers)):
 	squared_numbers.append(numbers[i]**2)
print(squared_numbers) # Output: [9, 49, 121, 225, 361]

2. What is a decorator in Python?
A decorator is a function that alters another function's behavior without changing its original code. Decorators can add functionality to existing functions, classes, or methods. 

3. Explain the concept of decorators in Python. How do they work, and what are some common use cases for them? Provide an example of a simple decorator function from the reading.

Decorators can add functionality to existing functions, classes, or methods. Decorators cover the original method with another method, which provides the changed outcome. For example, lower_case = [ letter.lower() for letter in ['A','B','C'] ]
upper_case = [ letter.upper() for letter in ['a','b','c'] ]
print(lower_case, upper_case)
OUTPUT: ['a', 'b', 'c'] ['A', 'B', 'C']

## Things I want to know more about

How can we use conditional statements with list comprehension to filter elements in a list?

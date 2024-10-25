Q1.Why do we call Python as a general purpose and high-level programming language?
Solution: Python is termed a general-purpose programming language because it can effectively tackle diverse tasks, ranging from building websites to analyzing data. It is labeled a high-level language due to its straightforward syntax and the way it simplifies complex hardware operations, making it user-friendly for novices and productive for seasoned programmers.


Q2. Why is Python called a dynamically typed language?
Solution : Python is called a dynamically typed language because variable types are determined at runtime rather than in advance. This means that you can assign a value of any type to a variable without explicitly declaring its type, allowing for more flexibility in coding but also requiring careful handling of type-related errors during execution.

Q3. List some pros and cons of Python programming language?
Solution Pros:
1.Easy to read and write, which makes it beginner-friendly.
2.Extensive libraries and frameworks for various applications.
3.Strong community support and documentation.
4.Versatile for different programming paradigms (object-oriented, functional, etc.).
Cons:
1.Slower execution speed compared to compiled languages like C or Java.
2.High memory consumption, which can be a drawback for memory-intensive applications.
3.Dynamic typing can lead to runtime errors that are hard to debug.

Q4. In what all domains can we use Python?
Solution : Python can be used in various domains, including:
1.Web development (Django, Flask)
2.Data analysis and visualization (Pandas, Matplotlib)
3.Machine learning and AI (TensorFlow, Scikit-learn)
4.Automation and scripting
5.Game development
6.Scientific computing (SciPy, NumPy)
7.Networking and cybersecurity

Q5. What are variables and how can we declare them?
Solution: Variables are used to store data values. In Python, you can declare a variable simply by assigning a value to it, like this:

x = 10  # Integer variable
name = "Alice"  # String variable
Q6. How can we take an input from the user in Python?
You can use the input() function to take input from the user. For example:


user_input = input("Enter something: ")

Q7. What is the default datatype of the value that has been taken as an input using the input() function?
Solution : The default datatype of the value taken as input using the input() function is a string.

Q8. What is type casting?
Solution : Type casting is the process of converting a variable from one data type to another. In Python, you can use functions like int(), float(), and str() to cast variables, for example:

num_str = "5"
num_int = int(num_str)  # Converts string to integer

Q9. Can we take more than one input from the user using a single input() function? If yes, how? If no, why?
Solution : Yes, we can take more than one input using a single input() function by splitting the input string. For example:

values = input("Enter two numbers separated by space: ").split()
This will give  a list of inputs.

Q10. What are keywords?
Solution : Keywords are reserved words in Python that have special meanings and cannot be used as identifiers (variable names). Examples include if, for, while, class, def, etc.

Q11. Can we use keywords as a variable? Support your answer with reason.
Solution : No, we cannot use keywords as variable names because they are reserved for defining the syntax and structure of the language. Using them as variables would lead to syntax errors.

Q12. What is indentation? What's the use of indentation in Python?
Solution : Indentation is the whitespace at the beginning of a line of code. In Python, it is used to define the scope of loops, functions, and classes. It indicates a block of code that belongs together, which is crucial since Python does not use braces for this purpose.

Q13. How can we throw some output in Python?
Solution : we can use the print() function to display output in Python. For example:
print("Hello, World!")


Q14. What are operators in Python?
Solution : Operators are special symbols that perform operations on variables and values. Python has various types of operators, including arithmetic, comparison, logical, assignment, bitwise, and more.


Q15. What is the difference between / and // operators?
Solution: The / operator performs floating-point division and returns a float, while the // operator performs integer (floor) division and returns the largest integer less than or equal to the result. For example:

print(5 / 2)  # Output: 2.5
print(5 // 2)  # Output: 2


Q16. Write a code that gives the following as an output.
Solution: 
print("iNeuroniNeuroniNeuroniNeuron")


Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
Solution : 
num = int(input("Enter a number: "))
if num % 2 == 0:
    print("Even")
else:
    print("Odd")


Q18. What are boolean operators?
Solution : Boolean operators are used to perform logical operations and return a Boolean value (True or False). The primary Boolean operators are and, or, and not. For example:
x = True
y = False
result = x and y  # Output: False


Q19. What will the output of the following?
```
1 or 0

0 and 0

True and False and True

1 or 0 or 0
```
Solution: 
1 or 0            # Output: 1
0 and 0           # Output: 0
True and False and True  # Output: False
1 or 0 or 0      # Output: 1


Q20. What are conditional statements in Python?
Solution : Conditional statements in Python are used to execute certain blocks of code based on whether a condition evaluates to True or False. They allow for decision-making in programs.



Q21. What is the use of 'if', 'elif', and 'else' keywords?
Solution:
if: Tests a condition and executes the following block of code if the condition is True.
elif: Stands for "else if" and checks another condition if the previous if was False.
else: Executes a block of code if none of the preceding conditions are True.



Q22. Write a code to take the age of a person as an input and display "I can vote" if age >= 18, and "I can't vote" if age < 18.
Solution: 
age = int(input("Enter your age: "))
if age >= 18:
    print("I can vote")
else:
    print("I can't vote")



Q23. Write a code that displays the sum of all the even numbers from the given list.
Solution: 
numbers = [12, 75, 150, 180, 145, 525, 50]
even_sum = sum(num for num in numbers if num % 2 == 0)
print(even_sum)  # Output: 342


Q24. Write a code to take 3 numbers as an input from the user and display the greatest number as output.
Solution: 
num1 = int(input("Enter first number: "))
num2 = int(input("Enter second number: "))
num3 = int(input("Enter third number: "))

greatest = max(num1, num2, num3)
print("The greatest number is:", greatest)




Q25. Write a program to display only those numbers from a list that satisfy the following conditions:
- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
Solution: 
numbers = [12, 75, 150, 180, 145, 525, 50]

for num in numbers:
    if num > 500:
        break
    if num > 150:
        continue
    if num % 5 == 0:
        print(num)
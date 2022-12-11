## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?
Ans - Because python isn't made for or used for anything specific. It can be used to create a variety of different programs.

Q2. Why is Python called a dynamically typed language?
Ans - In python, variables can change types during runtime. programming languages that don't have this feature are called statically typed languages

Q3. List some pros and cons of Python programming language?
Ans - 
----------
Pros
----------

dynamically typed language
interpreted language
vast libraries
open source
portability

----------
Cons
----------

slower compared to other languages like C,C++
Bad language for mobile development
Memory consumption is high
Limited data base access options
	

Q4. In what all domains can we use Python?
Ans - AI, ML, Deep learning, Game development, web development

Q5. What are variable and how can we declare them?
Ans - variables are containers that we can use to store data or values
we can declare a variable in python specifying the variable name and the value 
Example : 
	x = 10


Q6. How can we take an input from the user in Python?
Ans - input('what is your name : ');

Q7. What is the default datatype of the value that has been taken as an input using input() function?
Ans - String

Q8. What is type casting?
Ans - Type casting is the process of convert a variable's data type into another data type
Example : converting Integer to String

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
Ans - Yes, we can use the split method on input function to split the string received as inputs
Example : firstname, lastname =  input("Enter full name").split()
Nikhil Johny

Q10. What are keywords?
Ans - Keywords are reserved words which have a specific purpose. It can only be used for the specific purpose.

Q11. Can we use keywords as a variable? Support your answer with reason.
Ans - Keywords cannot be used as a variable. "Print" is a keyword which is used for printing something to the console.
If we try to use "print = 1" it will throw an error because the interpreter will think we are trying to use the print funciton.

Q12. What is indentation? What's the use of indentaion in Python?
Ans - Indentation is the spaces at the begining of a line of code. It is used for making the code more readable.
But in python indentation is used to represent a block of code

Q13. How can we throw some output in Python?
Ans - We can use the "raise" keyword to throw an Exception
Example : raise Exception("Division by zero")

Q14. What are operators in Python?
Ans - Operators in python are used to perform some computation. There are different types of operators in python
Arithmetic operators.
Assignment operators.
Comparison operators.
Logical operators.
Identity operators.
Membership operators.
Bitwise operators.

Q15. What is difference between / and // operators?
Ans - "/" operator performs a normal division and returns the full value (10 / 3 will be returned as 3.33) where are "//" operator is used to return an integer as the result of a division operation
 

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
Code 

```
print('iNeuroniNeuroniNeuroniNeuron')
```

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
Ans - 
num = int(input("Enter a number : "))
print("Even" if num % 2 == 0 else "Odd")

Q18. What are boolean operator?
Ans - Boolean is a primitive built in type which can only have 2 values, True or False.


Q19. What will the output of the following?
```
1 or 0 = 1

0 and 0 = 0

True and False and True = False

1 or 0 or 0 = 1
```

Q20. What are conditional statements in Python?
Ans - Conditional Statements are statements which can be used to check conditions in our program.
Example : if(a > b) print('a is greater')
	else print('b is greater')

Q21. What is use of 'if', 'elif' and 'else' keywords?
If-elif-else statement is used in Python for decision-making i.e the program will evaluate test expression and will execute the remaining statements only if the given test expression turns out to be true

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If ageage = int(input('Enter your age : '))
age = int(input('Enter your age : '))
print("I can vote " if age >= 18 else "I can't vote ")

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```

```
numbers = [12, 75, 150, 180, 145, 525, 50]
sum = 0
for num in numbers:
    sum += num if num % 2 == 0 else 0;
print(sum)
```


Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
```
num1 = int(input("Enter a number : "))
num2 = int(input("Enter a number : "))
num3 = int(input("Enter a number : "))
if num1 > num2 and num1 > num3:
    print(num1)
elif num2 > num3 and num2 > num1:
    print(num2)
else:
    print(num3)
```

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```

```
numbers = [12, 75, 150, 180, 145, 525, 50]
for num in numbers:
    if num % 5 == 0:
        if num > 500:
            break
        else:
            if num <= 150:
                print(num)
            else:
                continue
```
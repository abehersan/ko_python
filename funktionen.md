# Funktionen und Review!

## Berühmte Fragen zur Programmierung

Below are **10 exercises** to practice how we plan and write functions in Python. 
Included are tips and online resources to help you complete these tasks.

_Spoiler alert: some of these questions are often used in job interviews for Google, Meta and IBM._

**Tip: You can use online resources to help you solve a particular question.**

> If you complete 5 exercises, you get +5 Kiberonen extra. 

> If you complete 7 exercises, you get +10 Kiberonen extra. 

> If you complete all exercises, you get +20 Kiberonen extra. 

1. Write a function that takes a name (a string) and an age (an integer) as inputs and outputs the resulting string. 

    - Expected behavior:
    
    ```python
    # Input
    name = "José"
    age = 25
    # Output
    >> "Hi, my name is José and I'm 25 years old."
    ```

2. Write a function that takes two numbers, adds them together and determines if the result is an even number. 

    - Expected behavior:
    
    ```python
    # Input
    first_number = 1
    second_number = 11
    # Output
    >> "Sum = 12. Even? True"
    ```

3. Write a function that takes a list of numbers as an input and checks if the first and last items of the list are the same.

    - Expected behavior:
    
    ```python
    # Input
    input_list = [0, 10, 11, 2, 13, 0]
    # Output
    >> True
    ```

4. Write a function that prints the multiplication table of a given input number. 

    - Expected behavior:
    
    ```python
    # Input
    table_number = 2
    # Output
    >> 2, 4, 6, 8, 10, 12, 14, 16, 18, 20
    ```

5. Write a function that prints all odd numbers between 0 and 100. 

    - Expected behavior:
    
    ```python
    # Output
    >> 1, 3, 5, 7, 9, ..., 99
    ```

6. Define a die. Write a function that throws a die.

    - Expected behavior:
    
    ```python
    # Definition
    die = [1, 2, 3, 4, 5, 6]
    # Example output
    >> 4
    ```

7. Write a function that tells you if today is Saturday. 

    - Try using the ```import datetime``` command. Read its documentation. See [this link](https://www.delftstack.com/howto/python/python-datetime-day-of-week/) for a hint.

8. Write a function that accepts the diameter and returns the area of a circle. Then, show the circle with turtles. 

    - Remember that the area of a circle is $A = \pi r^{2}$, where $r$ is the radius of a circle.

9. Define a standard deck of cards. Write a function that draws 4 cards at random. 

    - See [this link](https://en.wikipedia.org/wiki/Standard_52-card_deck)

10. Define a function that takes an arbitrary amount of parameters and returns the maximum value. 

    - Investigate what ```*args``` is in Python. See [this link](https://realpython.com/python-kwargs-and-args/)
    
    ```python
    # Example function call
    myfunc(8, 9, 100, 20, 2, 1, ...)
    # Output
    >> 100
    ```
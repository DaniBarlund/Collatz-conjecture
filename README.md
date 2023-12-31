# Collatz Conjecture - Done in 2020

## Why make the project?

Idea of the project was to take an easy and simple mathematical concept that all could understand.
Then make it visually appealing as well as interactive for the user while learning to make my first gui.

## What is collatz conjecture?

Collatz conjecture, also known as 3x+1. Is the conjecture that all positive integers will end up in a loop 4-2-1 if two roles are applied to a any given positive integer.
Rules:
1. Number is even: x/2
2. Number is odd: 3*x+1
then recursive this until x is equal to one when it will end in that 4-2-1 loop.

For example take a number 5: 3*5+1=16, 16/2=8, 8/2=4, 4/2=2, 2/2=1. Then we have hit one and are in the loop.

## How to use it

1. Download Collatz Conjecture GUI.pyw and Function.py.
2. Run Collatz Conjecture from cmd with python "Collatz Conjecture GUI.pyw"
3. Give a starting value of positive integer and press **Input**
4. **Add** adds new line to the plot
5. **Update** updates plots if **Plot styles** or **Plot Colors** Are changed

### Example with the input value of 5
![Value of 5](https://github.com/DaniBarlund/Collatz-conjecture/blob/main/photos/value-of-5.png?raw=true)

### Example with multiple values**
![Multiple values](https://github.com/DaniBarlund/Collatz-conjecture/blob/main/photos/multiple-values.png?raw=true)

## How was the program done?

Gui was made with tkinter in python because it seemed to be fairly easy for a beginner to pick up. It had its pros and cons, mostly ran into trouble with .grid()
therefore the next project will be done with place instead. Everything else was nice and easy to understand and to play around with.

Graphing was done with matplotlib and it was a great and fun tool to visualize how differently numbers behave.
Worked perfectly for my use and would highly recommend.

Solving the list of numbers that lead to the 4-2-1 loop was made a couple if statements and recursion which stoped when the number equals one.
For each time the function runs it updates list that contains all the numbers and with that information the whole program works.

Things I would do differently:
Properly plan the layout of all widgets and not just try to fit them.
Use frames to divide window in to smaller pieces.


## Conclusion:
Project was a success,it took only a few days to make and I went from knowing nothing about graphical user interfaces to actually making a working one.
So learned a lot in a little time and I'm excited for the next project.

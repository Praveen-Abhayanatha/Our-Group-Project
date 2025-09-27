Group Project
🧮 Interactive Calculator Program
Task Description
The goal of this task is to create an interactive calculator that can:

Perform addition, subtraction, multiplication, division
Compute power and square root
Exit when the user chooses
We will implement the calculator using functions.
The program will keep running in a loop until the user selects exit.

Team Member: [1.Shiler Rahmani koukia 2.Praveen Abhayanatha 3.Behzad Bayat 4.Rishikesh Aditya Brahman 5.Muhammad Arsalan Durrani]

Algorithm of the Solution
Display a menu of operations to the user.
Take user input to choose an operation.
Based on the choice:
If it is addition, subtraction, multiplication, or division → ask for two numbers.
If it is power → ask for base and exponent.
If it is square root → ask for one number.
Perform the calculation.
Show the result.
Repeat until the user selects "exit".
import math
def calculater():
    while True:
      print('1 - addition') #when I enter num 1 it means addition
      print('2 - substraction') #when I enter num 2 it means substraction
      print('3- multiplication') #when I enter num 3 it means multiplication
      print('4- division') #when I enter num 4 it means division
      print('5- power' ) #when I enter num 5 it means power
      print('6- square root') #when I enter num 2 it means square root
      print('7 - exit') #when I enter num 2 it means exit
      choice = input('enter choise:')
      if choice == '1':
          num1 = float(input('enter first number:')) #enter your 1st num
          num2 = float(input('enter second number:')) #enter your 2nd num
          print('answer is', num1+num2) #it will print the answer
      elif choice == '2':
          num1 = float(input('enter first number:'))
          num2 = float(input('enter second number:'))
          print('answer is', num1-num2) 
      elif choice == '3':
          num1 = float(input('enter first number:'))
          num2 = float(input('enter second number:'))
          print('answer is', num1*num2) 
      elif choice == '4':
          num1 = float(input('enter first number:'))
          num2 = float(input('enter second number:'))
          if num2 != 0:
            print('answer is', num1/num2)
          else:
              print('invalid input')
      elif choice == '5':
          num = float(input('enter  number:'))
          print('answer is', num**2) 
      elif choice == '6':
          num = float(input('enter number:'))
          if num > 0:
            print('answer is', math.sqrt(num))
          else:
              print('invalid input') 
      elif choice == '7':
          print('exit')
          break
      else:
          print('invalid input')
answer = calculater()
1 - addition
2 - substraction
3- multiplication
4- division
5- power
6- square root
7 - exit
We added the calculator from this ![Calculator](https://upload.wikimedia.org/wikipedia/commons/3/3b/PocketCalculator.JPG)
This is the link to my Github repository
https://github.com/Praveen-Abhayanatha/Our-Group-Project.git


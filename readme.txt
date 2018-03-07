# Made by Jayden Abril & Jimmy Lembeck

from __future__ import print_function
import math
import random
import time

def intro():
  print("Welcome to Jayden & Jimmy's Quiz!")
  print(" ")
  raw = raw_input("Please enter your name: ")
  print(" ")
  time.sleep(.5)
  print("Welcome to the Quiz, ", raw, "!", sep="")
  print("You'll recieve 10 questions, including 4 options to choose from, good luck!")
  print(" ")
  print("Make sure you capitalize your letter!!!")
  time.sleep(1)
  question1()
  
def question1():
  money = 0
  cash = 0
  the = True
  while the == True:
    print(" ")
    time.sleep(1.5)
    print(" ")
    print("1. Which Country has the largest population?")
    print(" ")
    print("A. Russia, B. India, C. United States, D. China")
    print(" ")
    answer = raw_input("What is the answer?: ")
    if answer == "A":
      time.sleep(.5)
      print("You got it right!")
      money += 1
    if money == 1:
      cash += 500
      print('You recieved',cash,'dollars!')
      question2()
    else:
      print("Incorrect, you lose.")
      print(" ")
      print('Your total was: ',cash,'')
      retry()
  
def question2():
  money = 1
  cash = 500
  the = True
  while the == True:
    print(" ")
    time.sleep(1.5)
    print(" ")
    print("2. What is the only mammal that can't jump?")
    print(" ")
    print("A. Giraffes, B. Kangaroos, C. Lions, D. Elephants")
    print(" ")
    answer = raw_input("What is the answer?: ")
    if answer == "D":
      time.sleep(.5)
      print("You got it right!")
      money += 1
    if money == 2:
      cash += 500
      print('You recieved',cash,'dollars!')
      question3()
    else:
      print("Incorrect, you lose.")
      print(" ")
      print('Your total was: ',cash,'')
      retry()
    
    
def question3():
  the = True
  money = 2
  cash = 1000
  while the == True:
    print(" ")
    time.sleep(1.5)
    print("3. How many states are in the United States?")
    print(" ")
    print("A. 49, B. 50, C. 51, D. 52 ")
    print(" ")
    answer = raw_input("What is the answer?: ")
    if answer == "B":
      time.sleep(.5)
      print("You got it right!")
      money += 1
    if money == 3:
      cash += 500
      print('You recieved',cash,'dollars!')
      question4()
    else:
      print("Incorrect, you lose.")
      print(" ")
      print('Your total was: ',cash,'')
      retry()
    
def question4():
  the = True
  money = 3
  cash = 1500
  while the == True:
    print(" ")
    time.sleep(1.5)
    print("4. How many bones are in the human body?")
    print(" ")
    print("A. 207, B. 205, C. 206, D. 208 ")
    print(" ")
    answer = raw_input("What is the answer?: ")
    if answer == "C":
      time.sleep(.5)
      print("You got it right!")
      money += 1
    if money == 4:
      cash += 500
      print('You recieved',cash,'dollars!')
      question5()
    else:
      print("Incorrect, you lose.")
      print(" ")
      print('Your total was: ',cash,'')
      retry()
    
def question5():
  the = True
  money = 4
  cash = 2000
  while the == True:
    print(" ")
    time.sleep(1.5)
    print("5. How many genders are there in this world?")
    print(" ")
    print("A. 1, B. 2, C. 55, D. 60 ")
    print(" ")
    answer = raw_input("What is the answer?: ")
    if answer == "B":
      time.sleep(.5)
      print("You got it right!")
      money += 1
    if money == 5:
      cash += 500
      print('You recieved',cash,'dollars!')
      question6()
    else:
      print("Incorrect, you lose.")
      print(" ")
      print('Your total was: ',cash,'')
      retry()

def question6():
  the = True
  money = 5
  cash = 2500
  while the == True:
    print(" ")
    time.sleep(1.5)
    print("6. What is the world's highest mountain?")
    print(" ")
    print("A. Makalu, B. K2, C. KilimanJaro, D. Mount Everest ")
    print(" ")
    answer = raw_input("What is the answer?: ")
    if answer == "D":
      time.sleep(.5)
      print("You got it right!")
      money += 1
    if money == 6:
      cash += 500
      print('You recieved',cash,'dollars!')
      question7()
    else:
      print("Incorrect, you lose.")
      print(" ")
      print('Your total was: ',cash,'')
      retry()

def question7():
  the = True
  money = 6
  cash = 3000
  while the == True:
    print(" ")
    time.sleep(1.5)
    print("7. Which of these cities is not in Europe?")
    print(" ")
    print("A. Prague, B. Barcelona, C. Reyjkjavik, D. Moscow ")
    print(" ")
    answer = raw_input("What is the answer?: ")
    if answer == "D":
      time.sleep(.5)
      print("You got it right!")
      money += 1
    if money == 7:
      cash += 500
      print('You recieved',cash,'dollars!')
      question8()
    else:
      print("Incorrect, you lose.")
      print(" ")
      print('Your total was: ',cash,'')
      retry()    

def question8():
  the = True
  money = 7
  cash = 3500
  while the == True:
    print(" ")
    time.sleep(1.5)
    print("8. How many countries are there in the world?")
    print(" ")
    print("A. 205, B. 175, C. 143, D. 195 ")
    print(" ")
    answer = raw_input("What is the answer?: ")
    if answer == "D":
      time.sleep(.5)
      print("You got it right!")
      money += 1
    if money == 8:
      cash += 500
      print('You recieved',cash,'dollars!')
      question9()
    else:
      print("Incorrect, you lose.")
      print(" ")
      print('Your total was: ',cash,'')
      retry()   
    
def question9():
  the = True
  money = 8
  cash = 4000
  while the == True:
    print(" ")
    time.sleep(1.5)
    print("9. Which of the following countries do not border France?")
    print(" ")
    print("A. Germany, B. Italy, C. Netherlands, D. Spain ")
    print(" ")
    answer = raw_input("What is the answer?: ")
    if answer == "C":
      time.sleep(.5)
      print("You got it right!")
      money += 1
    if money == 9:
      cash += 500
      print('You recieved',cash,'dollars!')
      question10()
    else:
      print("Incorrect, you lose.")
      print(" ")
      print('Your total was: ',cash,'')
      retry()
    
def question10():
  the = True
  money = 9
  cash = 4500
  while the == True:
    print(" ")
    time.sleep(1.5)
    print("10. What does Wi-Fi stand for?")
    print(" ")
    print("A. Wireless Facility, B. Doesn't stand for anything, C. Wireless Fidelity, D. Wireless Fission ")
    print(" ")
    answer = raw_input("What is the answer?: ")
    if answer == "B":
      time.sleep(.5)
      print("You got it right!")
      print(" ")
      money += 1
    if money == 10:
      cash += 500
      print('You recieved',cash,'dollars!')
      ending()
    else:
      print("Incorrect, you lose.")
      print(" ")
      print('Your total was: ',cash,'')
      retry()
    
def retry(): 
  print(" ")
  print("Would you like to retry?")
  answer = raw_input("Type yes or no: ")
  if answer == "yes":
    print(" ")
    print(" ")
    print(" ")
    print(" ")
    question1()
  elif answer == "no":
    question1()
  else :
    question1()
    
def ending():
  print("Congragulations, you beat the quiz! You've been awarded 5,000 dollars!")
  print(" ")
  print("Do you want to do the quiz again?")
  answer = raw_input("Type yes or no: ")
  if answer == "yes":
    question1()
  elif answer == "no":
    time.sleep(2)
    print("the end")
    time.sleep(3)
    print("just kidding.. taking you back to quiz")
    print(" ")
    print(" ")
    print(" ")
    question1()
  else:
	  time.sleep(.5)
	  print
	  ending()

intro()

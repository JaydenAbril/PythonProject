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
  print("Make sure you capitalize the letters!!")
  time.sleep(1)
  question1()
  
def question1():
  the = True
  right = 0
  while the == True:
    print(" ")
    time.sleep(1.5)
    print(" ")
    print("Which Country has the largest population?")
    print(" ")
    print("A. Russia, B. India, C. United States, D. China")
    print(" ")
    answer = raw_input("What is the answer?: ")
    if answer == "A":
      time.sleep(.5)
      print("You got it right!")
      print("You recieved 500 dollars!")
      question2()
    else:
      print("Incorrect, you lose.")
      retry()
  
def question2():
  the = True
  right = 0
  while the == True:
    print(" ")
    time.sleep(1.5)
    print("What is the only mammal that can't jump?")
    print(" ")
    print("A. Giraffes, B. Kangaroos, C. Lions, D. Elephants ")
    print(" ")
    answer = raw_input("What is the answer?: ")
    if answer == "D":
      time.sleep(.5)
      print("You got it right!")
      print("You recieved 1,000 dollars!")
      question3()
    else:
      print("Incorrect, you lose.")
      retry()
    
def question3():
  the = True
  right = 0
  while the == True:
    print(" ")
    time.sleep(1.5)
    print("How many states are in the United States?")
    print(" ")
    print("A. 49, B. 50, C. 51, D. 52 ")
    print(" ")
    answer = raw_input("What is the answer?: ")
    if answer == "B":
      time.sleep(.5)
      print("You got it right!")
      print("You recieved 1,500 dollars!")
      question4()
    else:
      print("Incorrect, you lose.")
      retry()
    
def question4():
  the = True
  right = 0
  while the == True:
    print(" ")
    time.sleep(1.5)
    print("How many bones are in the human body?")
    print(" ")
    print("A. 207, B. 205, C. 206, D. 208 ")
    print(" ")
    answer = raw_input("What is the answer?: ")
    if answer == "C":
      time.sleep(.5)
      print("You got it right!")
      print("You recieved 2,000 dollars!")
      question5()
    else:
      print("Incorrect, you lose.")
      retry()
    
def question5():
  the = True
  right = 0
  while the == True:
    print(" ")
    time.sleep(1.5)
    print("How many genders are there in this world?")
    print(" ")
    print("A. 1, B. 2, C. 55, D. 60 ")
    print(" ")
    answer = raw_input("What is the answer?: ")
    if answer == "B":
      time.sleep(.5)
      print("You got it right!")
      print("You recieved 2,500 dollars!")
      question6()
    else:
      print("Incorrect, you lose.")
      retry()

def question6():
  the = True
  right = 0
  while the == True:
    print(" ")
    time.sleep(1.5)
    print("What is the world's highest mountain?")
    print(" ")
    print("A. Makalu, B. K2, C. KilimanJaro, D. Mount Everest ")
    print(" ")
    answer = raw_input("What is the answer?: ")
    if answer == "D":
      time.sleep(.5)
      print("You got it right!")
      print("You recieved 3,000 dollars!")
      question7()
    else:
      print("Incorrect, you lose.")
      retry()

def question7():
  the = True
  right = 0
  while the == True:
    print(" ")
    time.sleep(1.5)
    print("Which of these cities is not in Europe?")
    print(" ")
    print("A. Prague, B. Barcelona, C. Reyjkjavik, D. Moscow ")
    print(" ")
    answer = raw_input("What is the answer?: ")
    if answer == "D":
      time.sleep(.5)
      print("You got it right!")
      print("You recieved 3,500 dollars!")
      question8()
    else:
      print("Incorrect, you lose.")
      retry()    

def question8():
  the = True
  right = 0
  while the == True:
    print(" ")
    time.sleep(1.5)
    print("How many countries are there in the world?")
    print(" ")
    print("A. 205, B. 175, C. 143, D. 195 ")
    print(" ")
    answer = raw_input("What is the answer?: ")
    if answer == "D":
      time.sleep(.5)
      print("You got it right!")
      print("You recieved 4,000 dollars!")
      question9()
    else:
      print("Incorrect, you lose.")
      retry()   
    
def question9():
  the = True
  right = 0
  while the == True:
    print(" ")
    time.sleep(1.5)
    print("Which of the following countries do not border France?")
    print(" ")
    print("A. Germany, B. Italy, C. Netherlands, D. Spain ")
    print(" ")
    answer = raw_input("What is the answer?: ")
    if answer == "C":
      time.sleep(.5)
      print("You got it right!")
      print("You recieved 4,500 dollars!")
      question10()
    else:
      print("Incorrect, you lose.")
      retry()
    
def question10():
  the = True
  right = 0
  while the == True:
    print(" ")
    time.sleep(1.5)
    print("What does Wi-Fi stand for?")
    print(" ")
    print("A. Wireless Facility, B. Doesn't stand for anything, C. Wireless Fidelity, D. Wireless Fission ")
    print(" ")
    answer = raw_input("What is the answer?: ")
    if answer == "B":
      time.sleep(.5)
      print("You got it right!")
      print(" ")
      ending()
    
    else:
      print("Incorrect, you lose.")
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
  else:
	  time.sleep(.5)
	  print
	  ending()

intro()

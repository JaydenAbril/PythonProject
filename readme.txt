# Made by Jayden Abril & Jimmy Lembeck

from __future__ import print_function
import math
import random
import time
global questions

#-----------------------
#Defines questions and answers
#-----------------------

 
questions = [
"Which country was the largest?",
"What is the only mammal that cant jump?",
"How many states are in the US?",
"How many bones are in the human body?",
"How many genders are in this world?",
"What is the worlds highest mountain?",
"Which of these cities is not in Europe?",
"How many countries are in the world?",
"Which of the following countries do not border France?",
"What does Wi-Fi stand for?",]
global answers
answers = [
"A",
"B",
"C",
"D",
"A",
"B",
"C",
"D",
"A",
"B",
]
global printables
printables = ["""
A. Russia
B. India
C. United States
D. China
""",
"""
A.  Giraffes
B.  Elephants
C.  Kangaroos
D.  Lions
""",
"""
A. 49
B. 51
C. 50
D. 52
""",
"""
A. 207
B. 205
C. 208
D. 206
""",
"""
A. 2
B. 1
C. 55
D. 60
""",
"""
A. Makalu
B. Mount Everest
C. KilimanJaro
D. K2
""",
"""
A. Prague
B. Barelona
C. Moscow
D. Reykjavik
""",
"""
A. 205
B. 157
C. 143
D. 195
""",
"""
A. Netherlands
B. Germany
C. Spain
D. Italy
""",
"""
A. Wireless Facility
B. Doesn't Stand for Anything
C. Wireless Fidelity
D. Wireless Fission
"""]
#-----------------------
#Defines questions and answers
#-----------------------
 
def intro():
  print("Welcome to Jayden & Jimmy's Quiz!")
  print(" ")
  raw = raw_input("Please enter your name: ")
  print(" ")
  print("Welcome to the Quiz, ", raw, "!", sep="")
  time.sleep(1)
  questionf()
  


def questionf():
  the = True
  right = 0
  while the == True:
    noq = 0
    for question in questions:
      noq += 1
    q = random.randint(0,noq)
    questionno = questions[q]
    prints = printables[q]
    answe = answers[q]
    print("Your question is: ", questionno)
    print(" ")
    print(prints)
    print(" ")
    answer = raw_input("What is the answer?: ")
    abcd = ["a", "b", "c", "d"]
    if answer.lower() in abcd:
      print("You got it right!")
      right += 1
    else:
      print("Make sure you're entering an answer!")
      
    #-----------------------
    #Defines if you get a question right, you get this amount on money depending on how many questions you already got correct 
    #-----------------------
    
    if right == 1: 
      print("You recieved 500 Dollars")
      print(" ")
    if right == 2: 
      print("You recieved 1,000 Dollars")
      print(" ")
    if right == 3: 
      print("You recieved 1,500 Dollars")
      print(" ")
    if right == 4: 
      print("You recieved 2,000 Dollars")
      print(" ")
    if right == 5: 
      print("You recieved 2,500 Dollars")
      print(" ")
    if right == 6: 
      print("You recieved 3,000 Dollars")
      print(" ")
    if right == 7: 
      print("You recieved 3,500 Dollars")
      print(" ")
    if right == 8: 
      print("You recieved 4,000 Dollars")
      print(" ")
    if right == 9: 
      print("You recieved 4,500 Dollars")
      print(" ")
    if right == 10: 
      print("You recieved 5,000 Dollars")
      print(" ")
      
    #-----------------------
    #Defines if you get a question right, you get this amount on money
    #-----------------------

def goodtogo():
  random = 0

intro()

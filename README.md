========================================
FILE 1: welcome.py
========================================

def welcome(name):
    return "Hello, " + name + "! Welcome to PLP."


print(welcome("Amina"))
print(welcome("Brian"))
print(welcome("Fatuma"))


========================================
FILE 2: toolbox.py
========================================

def double(number):
    return number * 2


def is_pass(score):
    return score >= 50


def greet(name, greeting="Hello"):
    return greeting + ", " + name + "!"


print(double(7))
print(double(10))
print(is_pass(80))
print(is_pass(20))
print(greet("Amina"))
print(greet("Brian", "Habari"))


========================================

Expected "toolbox.py" output

14
20
True
False
Hello, Amina!
Habari, Brian!

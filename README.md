# Mini Project: Email Slicer
## Objectives 
1. Create a program to slice between username and email domain 
2. Create a Graphical User Interface (GUI) of email slicer

## Topics
1. Introduction to string variable
2. Introduction to looping (iteration)
3. Introduction to logical statement (IF-ELSE)
4. Introduction to Tkinter for GUI

## Algorithm
1. Input a email and assign to _email_ variable
2. Identify the length of _email_ variable and assign to N variable
3. Loop from i = 0 (as first index) to N
   1. if _email_[i] is equal to '@', then get a user name and assign to _username = email[0:i]_, get the domain name and assign to _domain = email[i+1,N]_. Exit the looping process.
   2. if _email_[i] is not equal to '@', then continue looping process
4. Print the output: _username_ and _domain_


---
layout: project
type: project
image: images/bank-square.jpg
title: Banking System
permalink: projects/banking-system
# All dates must be YYYY-MM-DD format!
date: 2020-10-26
labels:
  - C
  - C++
  - Unix
summary: A banking system module that read and store information using C/C++.
---

<img class="ui image" src="../images/banking-system.jpg">

## Description

The Banking System is a project that I made in ICS 212 at University of Hawaii in Manoa in 2020 Fall semester. It has five different functions: add, printall, find, delete, and quit. First of all, add is literally add the information about the user, such as name, address, and account number. And printall prints all the information that is stored in the system, and user can find their information by put account number in find function. Also, user can delete their information using delete function. Moreover, before the system is closed, it stores every information in the system and make a record so that it keeps the information. 

## What I gained from this project

In the mid-semester, it is first designed and developed using C language. Then, at the end of semester, the last project was to convert the banking system that is written in C to C++. By doing this project, I could learn about the differences and similarities between C and C++. Also, the project is written in Unix system, so I could learn some features of Unix. Furthermore, the debugging and testing the code is also a part of the project. So, I could learn how the testing is made and designed. 

## Snippet from Code

```js
while (quit == -1)
    {
        cout << "\n***********************  ICS 212 Banking System  ***********************\n";
        cout << "               Please choose an option from the menu below\n";
        cout << "=========================================================================\n\n";
        cout << "Add: Add a new record in the databse\n";
        cout << "Printall: Print all records in the databse\n";
        cout << "Find: Find record(s) with a specific account number\n";
        cout << "Delete: Delete existing record(s) from the database using account number\n";
        cout << "Quit: Quit the banking system\n\n";
        cout << "=========================================================================\n";
        
        validChoice = -1;
    
        cin.getline(userInput, 20, '\n');
```

Source code is available at: <a href="https://github.com/jubinc0911/banking_system"><i class="large github icon "></i>jubinc0911/banking_system</a>


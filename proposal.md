# X-Team 88 Project Student Database

See https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code for tips on using *Markdown* tags to format __.md__ files

## Goal

Work as a team to create a project proposal for your X-team to complete together.
The project does not have to be extremely difficult,
but there must be work to do for each member of your team.
You may reference figures using "See figure 1".  
Be sure to submit corresponding image files, i.e. figure1.png (or figure1.jpg) for each figure.

## Grading: To earn full credit, your team's proposal must include:

* (md) documentation: [this file] describing purpose and use of your program

* Description of a program that has:

  ** a main Java program class in a file named Main.java
  
  ** a custom data structure designed and built by your team
  
  ** comprehensive testing of individual units
  
 Caution: You are not being asked to implement this program, at least not yet. 
 We just want your group to make a proposal or pitch for your program.
 
 Tip: Your custom data structure can be composed of or extensions of data structures that you have learned and used in previous programming assignments.  We're looking for decisions about how to build a high-level data structure that will likely have lower-level components.

## Problem Description

Briefly describe a problem that your team would like to solve.  
Describe at a high level a program that could solve that problem.

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)

Student Database

2. Output: Describe the output your program will produce.  Include and example format of the output produced.
The output of the program will include information of students ranging from student ID, GPA, courses, etc.


3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.

Data: First Name, Last Name, Major, Standing, Age, GPA, Courses Taken, Credits..
[ID] [Last Name] [First Name] [Age] [Standing] [Age] [GPA]... 

4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.

There will be options to search students by name or user ID. This will be implemented through a dropdown bar and text entry. The user can then select the student to see more information about them. There will be options to add additional courses or update GPA.

5. Types List: Break your solution idea down into units that you think can be implemented with a single class. Name each interface or class and briefly describe its function or purpose.

HashTable class implementing the hashtable // store Student Objects
 put(){} get(){} remove(){} basic functions of hashtable

HashTableADT class implementing the hashtable structure // structure for basic Hashtable methods
 put(){} get(){} remove(){} basic functions of hashtable

Student class student object with various values (ID, GPA...) // student information
 search(){} get a student and related information
 showAllByName(){} show all students names in alphabetically

## Edit and Submit this file and any figures referenced by this document.

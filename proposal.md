# X-Team 39 SGTS-Student Grade Tracking System Proposal

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

Make a convenient way to access students' grades, and create a program to help professors to track the performance of students. The program will implement a hashtable to store each student's grades and personal information.

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)

	Proposal to create a student grade tracking system


2. Output: Describe the output your program will produce.  Include and example format of the output produced.
	
	When the user asks for the performance of a student, the student's information, grade for each test, class average for each test and average score will be generated. When the user asks for the list of all students in the database, the program will show the names and the IDs of all students. 

	Sample Output:
	a) A student's info
	--------------------
	Student ID: 123456789
	Student Name: xxxxx
	
	Grades:
	Test1:90	
	Test2:98	
	Test3:87	
	...

	Performance Analysis:
	Average:79
	Highest:90
	Lowest:67
	---------------------

	b) List of students
	---------------------
	AAAA 123456789
	BBBB 222222222
	CCCC 313131311
	--------------------
	

3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.
	
	In order to add a student, a String "Name" and a int number is required.
	After a student's info is added, we can add grade to that student by inputting a String 	"Test name" and the score of that test, which is a int number.
	After a student's info and grades are added, we can view the info and all scores of the 	specific student by inputting the ID or the name of a student.
	All students' info will be displayed if user choose the 'list' button.

	-----Add student------
	John Fisher 123456789
	----------------------

	-----Add Grade--------
	John Fisher ChemMidTerm 97
	----------------------
	or
	----------------------
	123456789 ChemMidTerm 64
	----------------------

	-----Search for student------
	John Fisher	
	-----------------------------
	or 
	-----------------------------
	123456789
	-----------------------------

	-----List all students-------
	list
	-------------------------------


4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.

The function of the implementation contains: add, search, edit, list. The homepage contains the 4 buttons which would carry out tasks of adding data in the list, retrieving data from the list. User click one of the button to get into the subpage. In the add page, user enter the name or student id in the list. In the edit page, enter the student name or ID and their grade information to be stored in the list. In the search page, enter student name or ID to retrieve the student information from the list. In the list page, get the list. 


5. Types List: Break your solution idea down into units that you think can be implemented with a single class.

	We could implement this using one hash table class and a general node class that takes comparable variables as parameters.
	HashTable - The hash table interface will include add, search, and remove. This will be used to store the given students' data in an efficient manner.
	add - used to add a student's information into the hash table
	search - used to find a student's information
	remove- used to remove a student's information from the hash table
			
			
	Node - The node class will allow Integer and String to be used for the key and any compable types for the information stored within the node. This will be used to store the given student's grades and link them to their student ID and Name.
	Its interface will include average, lowest, and highest.
	average - calculates a student's average of their test score.
	lowest - gets a student's lowest test score
	highest - gets a student's highest test score



## Edit and Submit this file and any figures referenced by this document.


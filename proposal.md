# X-Team NN Project Proposal

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



2. Output: Describe the output your program will produce.  Include and example format of the output produced.



3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.



4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.



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
		
Name each interface or class and briefly describe its function or purpose.


## Edit and Submit this file and any figures referenced by this document.


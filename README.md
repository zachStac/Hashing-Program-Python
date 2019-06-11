# Hashing-Program-Python

Goal: build a program to experiment with hashes and how to implement hashes using python. Test the differences between the algorithms, for example SHA256 and MD5. Find some way to hash and then store the hashes for reference later. This will be needed for the salt project latter. Also find a way to implement the hash right into a data base, for this it will need to be recoded most likely. Think about the program acting as a plugin to the data base.

To Do:  
	Build a base program to hash some kind of user input
	Test the different hash kinds, or hashing algorithms 
	Build a function to test saved hashes with clear text user input
	Build a function to store  hashes externally in a text file
	Make shure the hash is store after being encoded 
	Build functions to hash using serval algorithms
	Build a CMD interface for the program 
	Build a GUI interface for the program 
	Have a version that will interface with a data base
	Try to make my own hashing algorithm 

Project: 
•	I began by using a library called secrets but I ran into a set of problems.
•	I then used a library called hashlib which allowed me to pick form a series of algorithms I then use an import as hlib to save space later. VERSION1
•	At first I built one function that would do the hashing of the user input. The base program in this state used sha256 for the hashing algorithm. Note to view the input after it has been hashed the string needs to encoded. I need to look into encoding the output before it is to be exported out of the program for storage. To view the data it also has to be displayed as hexa-digest or the string will appear as just a bunch of nonsense to the clear text reader/ inturpriture. VERSION1
•	Then I added a function that can be called by a user if they wish to test a hash they did earlier. Note at this state of the program there is no storage system yet, so any hash has to be checked at the same time of the hash creation. Note to display the encoded string it has to be presented with a hexa-digest call. VERSION2
•	


# -Social-Network-Graph-Application
 A social network graph application that reads user data from a file and provides functionalities to view a user's friends list and check the connection path between two users. It uses a file reader to load data, a Record class to store user info, and a PathFinder class to determine the shortest path using BFS.

INSTRUCTIONS

Social Network Graph Application
This application simulates a social network graph, where users can check their friends list and find connections between any two users.

Requirements
Java Development Kit (JDK) 8 or higher
Usage
Compile the Code

sh
Copy code
javac Main.java FileReader.java Record.java PathFinder.java
Run the Application

sh
Copy code
java Main
Follow the On-screen Prompts

Input the file path containing user data.
Choose options from the main menu to interact with the application.
File Format
The input file should follow the format:

First line: Total number of users and total number of connections.
Subsequent lines: Pairs of user IDs representing connections.
Example:

Copy code
5 4
0 1
1 2
2 3
3 4
Main Menu Options
Get Friend List

Enter a user ID to see the list of friends for that user.
Get Connection

Enter two user IDs to see the connection path between them if it exists.
Example Session
Get Friend List

mathematica
Copy code
Enter ID of person: 1
Person 1 has 2 friends!
List of friends: [0, 2]
Get Connection

vbnet
Copy code
Enter ID of person A: 0
Enter ID of person B: 3
There is a connection from 0 to 3!
0 is friends with 1
1 is friends with 2
2 is friends with 3

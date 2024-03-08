# ChessAI
This code is used to implement a simple Chess-playing program. Specifically, the code for the Custom agent was created for this project. Each agent (Custom, Random, Greedy, Novice, Intermediate, Beginner, and Human) will play against the other agents and be scored based on a number of criteria. The results are then compiled in results.html.

The purposes of each of the following files are stated below:

agents - a folder containing all agents that play against each other
- custom.jar
- random.jar
- greedy.jar
- novice.jar
- beginner.jar
- intermediate.jar
- human.jar

classes - a folder containing Java class files
- CustomAgent.class
- GameTree.class
- Result.class

src - a folder containg the source code
- CustomAgent.java - implements the Custom agent
- GameTree.java - used by CustomAgent.java to track and change various pieces of information related to the state of the game and possible moves
- Result.java - used by CustomAgent.java to store a particular state and associated value

All other files under the src directory are part of an external chess framework.

chess.jar - a program to run a series of chess matches between the provided agents

To compile and run the program, run the run-chess.bat file (Windows) or the run-chess.sh file (Mac/Linux).

To view the results, open the results.html file.

Code is available upon request.

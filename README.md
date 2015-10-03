# RobotTurtlesAutomation
Create Automation platform for Robot Turtles Game

## Introduction:

Robot Turtles is a game that was created by Dan Shapiro to help teach the principles of programing to kids.  Haveing played it a bit, it is primarily a logic game consisting of Forward, Left and Right command cards that that you lay out in series to provide the "code" for your game piece (turtle) to move from it's corner to the corisponding colored target (Gem) on the game board.  From the first time I played the game with my kids I thought it would be even more interesting to automate the pieces.  This project is my ideas and planning towards making that happen.

##Goal:

Create basic wireless robotic turtles capable of taking commands from a micro-controller to perform the tasks of the game.  Commands will be entered with one 4 button control pad per Robot Turtle that includes:
- Forward
- Left
- Right
- Debug (Undo Last Command)
The Controller will include an LCD readout that shows all imputs for entire game in the form of Arrow Icons.

##Details:

- Game Board Layout: 8x8 grid consisting of 64 squares that are 2&2/16in by 2&2/16in.
	- 32 squares are inside spaces that are quad-directional
	- 28 squares are edge spaces that are tri-directional	
	- 4 squares are corner spaces that are bi-directional
- 4 Moving Pieces
- 4 Static Targets
- X Static Blocking Piecies (Stubbed)
	- X Ice
	- X Solid
- X Modifier Pieces (Stubbed)
	- X Laser
	- X Function
- Movement Requirements
	- Standard
		- Forward:  Move 2&2/16 inches @ 90deg
		- Right:  Turn 90deg then move 2&2/16 inches @ 0deg
		- Left:  Turn -90deg then move 2&2/16 inches @ 0deg
	- Debug Movements (Undo Last Move)
		- rForward:  Move 2&2/16 inches at 180deg
		- rRight:  Turn -90deg then move 2&2/16 inches @180deg
		- rLeft:  Turn 90deg then move 2&2/16 inches @180deg

##Roadmap:

	- Build Basic Robots
	- Complete gameboard integration for quickstart game (No obstacles)


##Parts





## References:
Dan Shapiro:
- https://twitter.com/danshapiro
Robot Turtles:
- https://www.kickstarter.com/projects/danshapiro/robot-turtles-the-board-game-for-little-programmer
Arduino:
- https://www.arduino.cc/

# CS1666 Team EXAMPLE

## Team Members
* Physics sub-team
	* Jacob Zomper
		* Pitt ID: jlz43
		* GitHuber username: jacob-zomper
	* Nicholas Farnan
		* Pitt ID: nlf4
		* GitHuber username: nfarnan
	* Nicholas Farnan
		* Pitt ID: nlf4
		* GitHuber username: nfarnan
* Random level generation sub-team
	* Dilan Ozkaynak
		* Pitt ID: dio4
		* GitHuber username: dilan-dio4
	* Nicholas Farnan
		* Pitt ID: nlf4
		* GitHuber username: nfarnan
* Networking sub-team
	* Nicholas Farnan
		* Pitt ID: nlf4
		* GitHuber username: nfarnan
	* Nicholas Farnan
		* Pitt ID: nlf4
		* GitHuber username: nfarnan
	* Nicholas Farnan
		* Pitt ID: nlf4
		* GitHuber username: nfarnan
	* Nicholas Farnan
		* Pitt ID: nlf4
		* GitHuber username: nfarnan
* AI sub-team
	* Matt Darden
		* Pitt ID: mtd38
		* GitHuber username: mattdarden
	* Nicholas Farnan
		* Pitt ID: nlf4
		* GitHuber username: nfarnan
	* Nicholas Farnan
		* Pitt ID: nlf4
		* GitHuber username: nfarnan
	* Nicholas Farnan
		* Pitt ID: nlf4
		* GitHuber username: nfarnan

## Game Description

For our project, we will build a clone of NES Hockey. We want players to be able
to play full games of 5 on 5 hockey with user-set period times. Players should be able
to skate around the rink, pass the puck, shoot, check other characters (potentially
causing the puck to come loose). Players will either be able to play each other
using networked multiplayer, or play single-player against an AI-controlled team.


## Specific Milestones

* Playing full 3-period games of hockey with score tracking.
* Will only implement 2 teams (red and blue)
* Will only have 1 stadium option available
* Players will be able to take control of any of the on-screen hockey players
* All characters (except the goalie) will be given free movement around the rink
* Goalie will be limited to moving directly in front of the net

## Advanced topics

* Physics
	* Simulated accurate bouncing of the puck off of the boards surrounding the rink
	* Accurately simulate the slowing down of the puck as it glides accross the ice on a pass or shot
	* Simulate players bouncing off of one another on collision (checks)
* Networking
	* Allow 2 players to connect to a single game instance and play the game as a lag-free experience
* AI
	* Computer-controlled characters should actively track towards the puck when it is loose
	* Should make decisions as to when to shoot or pass

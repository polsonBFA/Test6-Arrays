# Chapter 5 Test - Writing Classes

**Instructions**

We have been studying classes this past unit - and some of you may recall watching World Cup Soccer in 2022. For your test today you'll be writing and testing a SoccerTeam class. 

The required elements are described below. Please read them carefully and enjoy!

-Inspired by an example in *Java Methods - Object-Oriented Programming and Data Structures* by Litvin/Litvin and by World Cup 2022.


**Steps**
1. Write a class SoccerTeam with instance variables that hold the team name (i.e. country), the number of wins, losses, and ties. Include an appropriate constructor for the class.
2. Write a method that returns this team's current number of points (each win is three points, each tie is one point).
3. Write a reset method that zeroes out this team's wins, losses, and ties.
4. Write a played method that compares the number of goals scored in a match by this team and other team and increments the appropriate fields (wins, losses, ties) for both teams.
5. Add fields to keep track of the total number of matches played and the total number of goals scored by all teams in a tournament, combined. Ensure that this value is updated with each match that is played.
6. Add static accessor methods for these two fields and a static resetTournament method to zero them out.
7. Write a toString method that returns a string with team name, wins, losses, ties and points as shown. For example "Portugal: 2 1 0 6" would represent 2 wins, 1 loss, 0 ties, and 6 points for Portugal.
8. Test your class: In the Main.java write a program that defines four teams and has them "play" their Group Stage matches. After completing the matches, report each team's standing as well as the total number of matches played and the total number of goals scored by all teams in the tournament. An example of the output desired is below:

Qatar: 0 3 0 0 <br>
Ecuador: 1 1 1 4<br>
Senegal: 2 1 0 6<br>
Netherlands: 2 0 1 7<br>

Matches Played: 6<br>
Goals Scored: 15<br>
   
Resources
Use the link below to select a group in the World Cup 2022 to simulate.<br>
[Matches](https://www.bbc.com/pidgin/sport-63818464)


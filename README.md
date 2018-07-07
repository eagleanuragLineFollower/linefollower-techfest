# linefollower-techfest
## **Linefollower robot for Techfest 16**
Code as Run during the event.
Linefollower is an automatic and self contained robot that solves mazes in order to reach a final goal position. Though we had an impressive run, we placed 6th in the event : /

## Code
The code is made of two files: Bot.ino, which contains the Arduino Specific Parts of the code and Graph.cpp which is an implementation of Dijkstra's Shortest Path Algorithm trimmmed down for the small Arduino Uno.
Algorithm works by first doing standard DFS in Explore Mode and exploring all Nodes, then switching to Wait mode and after pressing a button, it finds the shortest path and follows it in Path mode. theres also a Panic Mode in case anything goes Wrong.

If complied on Arduino IDE, the entrypoint is in Bot.ino. 
For testing purposes, it can be compiled directly to .exe and the algorithm may be tested using the autotest.py GUI in /Test.

![Cerificate Linefollower](https://raw.githubusercontent.com/s-ankur/linefollower-techfest/master/techfest.png)

![Watch The Aftermovie](https://www.youtube.com/watch?v=2z3CEBv8PLI)

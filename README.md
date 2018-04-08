# AT
## Personnel
Andrew Chopey
Tiffany Zhong
## Statement of Problem:
What is the boolean value of the statement "it's possible to get from the starting position to treasure"?
## Recursive abstraction:
When I'm asked to return the boolean value from the current position, the recursive abstraction can return the boolean value of the statement is it possible to reach the treasure from the next position.
## Base case
1)When the pathfinder can not make another valid move without backtracking.
## English or pseudocode description of algorithm
For each junction check:

  if the junction is valid and hasn't been crossed before
  
      if true than invoke the recursive abstraction
      
  else if the pathfinder has reached the treasure 
  
      return true
      
  else
  
      invoke the base case and then recursively backtrack
      
If all junctions from the starting position have been checked and returned false then return false.

## Class(es), with fields and methods
## Version*n* wish list

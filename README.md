# wk10-tower-of-hanoi
Implement popular Tower of Hanoi problem for number of disks specified by user.  
In this problem, we're given disks of different sizes stacked from smallest on top to largest at bottom on (say) PegA.  Challenge is to move them to a differnt PegC one at a time using an intermediate PegB.  Constraint is that a bigger Peg can never be placed on a smaller peg.  
This is an O(2^n -1) problem, where the number of steps roughly doubles for each additional disk.  It is therefore solvable in realistic time for only a relatively small number of disks.

## To Execute this Repo
1. Clone this repo
2. Load index.html into a browser
3. In the text box on top-left, enter a value for disks to use in the Tower of Hanoi problem.  Default is 5 disks.
4. Press the "Make Move" button to step through the solution
<br>
**Credit: MIT xPRO: Professional Certificate in Coding: Full Stack Development with MERN - September 2021**

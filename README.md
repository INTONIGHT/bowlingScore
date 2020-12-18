# bowlingScore
This is a coding project which is simple but still challenging.
The goal is to create a program that calculates score in bowling. 
you are given 10 frames usually with 2 rolls per fram. up to 10 pins knocked down
if the first rolls knoks down all 10 strike frame finished.
Second roll knocks down remainder of 10 then its a spare.
10th fram can have 3 rolls if the first roll is a strike or the second a spare.
if not a spare nor strike add the two rolls together for the frame. if spare then add the two rolls then the next roll which gives you the score for the frame. strike add the two rolls for the fram plus the next two rolls giving the frame score. the score of the game is the sum of all the frames.
object oriented 10 frames max all inpus valids. tests written to ensure code works.
Example input
[
    [1,2],
    [10,nil],
    [5,4],
    [7,3],
    [10,nil],
    [10,nil],
    [1,4],
    [6,2],
    [7,3],
    [10,3,7],
]
example output 
frame scores:3,19,9,20,21,15,5,8,20,20
game score :140
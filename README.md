# Tower-Of-Hanoi
Tower Of Hanoi Problem is solved in java using the recursion.

The Tower of Hanoi problem is a classic problem that can be solved easily usingrecursion, but it is difficult to solve otherwise.

The problem involves moving a specified number of disks of distinct sizes from one tower to another while observing the following rules:

 ■ There are n disks labeled 1, 2, 3, . . . , n and three towers labeled A, B, and C.
 
 ■ No disk can be on top of a smaller disk at any time.
 
 ■ All the disks are initially placed on tower A.
 
 ■ Only one disk can be moved at a time, and it must be the smallest disk on a tower.
 
The objective of the problem is to move all the disks from A to B with the assistance of C. For example, if you have three disks, the steps to move all of the disks from A to B are shown in the figure

![image](https://user-images.githubusercontent.com/24220136/230293840-b154755e-f911-4607-bfd9-901ed1064f87.png)

Analyze the Tower of Hanoi Problem.

The Tower of Hanoi problem recursively moves n disks from tower A to tower B with the assistance of tower C as following:
1. Move the first n-1 disks from A to C with the assistance of tower B
2. Move disk n from A to B
3. Move n-1 disks from C to B with the assistance of tower A

The complexity of the algorithm is measured by the number of moves. Let T(n) denote the number of moves for the algorithm to move n disks from tower A to tower B with T(1)=1.

![image](https://user-images.githubusercontent.com/24220136/231625022-abf145d3-d38f-4e94-821c-75a5fc1df56d.png)

Output of the implementation in the case of 4 disks example:

![image](https://user-images.githubusercontent.com/24220136/230294033-e6ea37ca-4766-41f5-8c13-8dac1fb9f4e9.png)


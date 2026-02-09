# Sprial_Matrix-II-problem
 We here solve Given n, generate an n x n matrix filled with numbers from 1 to n² in spiral order.We keep 4 boundaries and move in a spiral ,top:-left to right  right::-top to bottom  bottom :- right to left  left :-bottom to top.


 # Apporach to solve the problem

 To solve this problem, we  fill the matrix layer by layer in a spiral pattern.

We maintain four boundaries to fill the matrix spirally 

top → starting row

bottom → ending row

left → starting column

right → ending column

We fill numbers in the following order:

Left → Right (top row)

Top → Bottom (right column)

Right → Left (bottom row)

Bottom → Top (left column)

After completing one spiral cycle, we shrink the boundaries and continue until all numbers are filled.


# Time Complexity used 
O(n2)

# Space Complexity used 
O(n2)


Add your answers to the Algorithms exercises here.

Exercise I

a) O(n) as the while loop iterates once from 0 to n^3
b) O(n^4) as 3 for loops are nested inside a for loop hence O(n) * O(n) * O(n) * O(n)
c) O(n) as the it loops through the input -1 each time

Exercise II
- Create an anchor to find middle floor
- Set it to f
- Create if statement to check if egg gets broken if it is thrown
- If egg is broken, find the middle floor of the left side and test again
- Else If egg doesn't break, do the same to the right side and check if the egg still doesn't break
- If egg break on the right side, go left
- Repeat this process until we find the exact floor where an egg breaks or doesn't break
- runtime complexity of this solution would be O(log n)



# bubble-sort

Here's the algorithm for the given code:

1. Start the program.
2. Define a function Bubble that takes an integer array and its size as parameters.
3. Declare variables passes, comparisons, i, j, and temp of type integer.
4. Set passes and comparisons variables to n-1 where n is the size of the array.
5. Use a nested for loop to iterate through the array.
6. For the outer loop, set the loop variable i to 0 and continue while i is less than passes.
7. For the inner loop, set the loop variable j to 0 and continue while j is less than comparisons minus i.
8. Inside the inner loop, compare the value of the array at j with the value of the array at j+1.
9. If the value of the array at j is greater than the value of the array at j+1, swap the two values using a temporary variable temp.
10. After completing the inner loop, increment the value of the outer loop variable i by 1.
11. Print the first and last element of the sorted array.
12. Define the main function.
13. Declare an integer array arr with 5 elements and initialize it with some values.
14. Call the Bubble function passing the array arr and its size 5 as arguments.
15. End the program.

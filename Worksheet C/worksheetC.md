1a)
This algorithm will start at i = 0 and do every j value, so when i = 0 j = 1 , j = 2 ..... and so on until j = n -1, after this i will be set to 1 and it will cycle through every value of j again. This will continue until the numbers in the list are equal but the number they are in the list are not the same. For example if the 7th number in list j and the 5th number in list i were equal the program would end. This tells us if there are duplicated in this list. 

1b)
This algorithm is quadratic because it has 2 for loops, it needs to cycle through n values of j for every value of i up until i = n. The amount of operations would look like n + n + n + n for each value of i this would continue n amount of times therefore the amount of operations would be nxn making it quadratic. 

1c)
Because every possible output for i and j is still being compared.

1d)
The first algorithm compared values at the beginning well but when i increases to 1/2 of n it will have taken half the time to process the algorithm but will have compared a lot more than half of all the possible output combinations (it will have roughly compared 75% of all possible output combinations) . The new algorithm reduces the time by constantly checking 1 new output combination each time and does this with far fewer comparisons or in this case operations

1e)
No it is no longer quadratic, if the original sample size was 10 and you make it 11 you are only adding another 11 operations for the algorithm to check all the possible outcomes. 

1f)
O(N Log N)[1]

1g)
0(N)
The time complexity in this case is the linear, a logarithmic time complexity is usually faster than linear and what determines an algorithms time complexity is the one that takes the longest. In this case however if the sample size is greater than 10 the sort takes longer than the linear for loop.

1h)
The second algorithm is likely to run faster as it simply as less operations to do,  the nature of the function 0(N LogN) means that if you add 10000 more values to sort it will take 10000 more operations to sort and another 10000 to compare. On the other hand the first algorithm if you added 10000 more operations you would be looking at 1 + 2 + 3 + 4...... Until 10000 that sum will far exceed the second algorithm.

1i)
If the order in which it recognised the duplicates values is important, the act of sorting may ruin the integrity of the list. 


[1](https://www.ics.uci.edu/~pattis/ICS-33/lectures/complexitypython.txt)



# The-Primes

The Primes

Description


|---|---|---|---|---|

| 1 | 1 | 3 | 5 | 1 |

|---|---|---|---|---|

| 3 | 3 | 2 | 0 | 3 |

|---|---|---|---|---|

| 3 | 0 | 3 | 2 | 3 |

|---|---|---|---|---|

| 1 | 4 | 0 | 3 | 3 |

|---|---|---|---|---|

| 3 | 3 | 3 | 1 | 1 |

|---|---|---|---|---|

(Figure 1)


Figure 1 shows a square. Each row, each column and the two diagonals can be read as a five digit prime number. The rows are read from left to right. The columns are read from top to bottom. Both diagonals are read from left to right. Write a program that constructs such squares:


    The prime numbers must have the same digit sum (11 in the example).
    The digit in the top left-hand corner of the square is pre-determined (1 in the example).
    A prime number may be used more than once in the same square.
    If there are several solutions, all must be presented.
    A five digit prime number cannot begin with zeros, ie 00003 is NOT a five digit prime number. 



Input

Your program is to read from standard input. First the digit sum of prime numbers and then the digit in the top left-hand corner of the square. The file contains two lines. There will always be a solution to the given test data.

Output

Your program is to write to standard output. Output five lines for each solution found, where each line in turn consists of a five digit prime number. The solutions are sorted by the prime in the first row, then by the prime in the second row,etc. Output a blank line after each solution.

Sample Input

11
1

Sample Output

11351
14033
30323
53201
13313

11351
33203
30323
14033
33311

13313
13043
32303
50231
13331

# Questions : Week 3

## Question 1: word_order

You are given words. Some words may repeat. For each word, output its number of occurrences. The output order should correspond with the input order of appearance of the word. See the sample input/output for clarification.

> Note: Each input line ends with a "\n" character.

Input Format

The first line contains the integer. The next lines each contain a word.

Output Format

Output lines. On the first line, output the number of distinct words from the input. On the second line, output the number of occurrences for each distinct word according to their appearance in the input.

```bash
Sample Input :
4
bcdef
abcdefg
bcde
bcdef

Sample Output :
3
2 1 1
```

[Go to reference](https://www.hackerrank.com/challenges/word-order/problem)

## Question 2: tic_tac

Tic-tac-toe is a pencil-and-paper game for two players, X (ascii value 88) and O (ascii value 79), who take turns marking the spaces in a 3×3 grid. The player who succeeds in placing three respective marks in a horizontal, vertical, or diagonal row wins the game. Empty space is represented by \_ (ascii value 95), and the X player goes first.
The function nextMove takes in a char player, and the 3x3 board as an array. Complete the function to print 2 space separated integers r and c which denote the row and column that will be marked in your next move. The top left position is denoted by (0,0).

```bash
Example input:
X
___
___
_XO

Example output:

1 0
```

How does it work? Your code is run alternately with the opponent bot for every move.

[Go to reference](https://www.hackerrank.com/challenges/tic-tac-toe)

## Question 3: motu_patlu

Motu and Patlu are very good friends and they love to eat ice-creams. Once they thought of playing a game, so they bought “n” ice-creams from the market of varying heights (may be same). They arranged the ice-creams in a line in random order. Motu starts to eat ice-creams from left to right and Patlu from right to left. The heights of the ice-creams are known.

Motu eats the ice-cream as twice the speed of Patlu (that’s the secret for his health :p ). If, anyone of them is eating the ice-cream , then definitely other one cannot have that ice-cream. However, if both of them reach the same ice-cream, Motu snatches it away from Patlu (he got more power than patlu :( ) and eats it. The winner will be the one who will eat more number of ice-creams.

Since, both of them are too busy in eating ice-creams they forgot to count the number of ice-creams they have already eaten. Can you help them in deciding the winner.

P.S. - Since, ‘WINTER HAS ALREADY ARRIVED’ ,so ice-creams will not melt as it is freezing out there.

Note : Time taken to eat a ice-cream is directly proportional to its height.

Input :

The first line contains one integer t, the number of test cases.

The first line of each test case contains one integer n,the number of ice-creams.

The second line contains a sequence , a1, a2, a3 . . . an where ai denotes height of ith ice-cream.

Output :

For each test case print two new lines.

First line contains two spaced integers, the no. of ice-creams eaten by Motu and Patlu respectively.

Second line contains the name of the winner, if motu eats more no. of icecreams print ‘Motu’ (without inverted commas), if patlu eats more no. of ice-creams print ‘Patlu’ (without inverted commas). In case of Tie print ‘Tie’ (without inverted commas).

```bash
SAMPLE INPUT:
3
5
2 6 2 1 7
4
15 2 1 3
5
2 4 12 4 7

SAMPLE OUTPUT:
4 1
Motu
1 3
Patlu
3 2
Motu
```

[Go to reference](https://www.hackerearth.com/practice/algorithms/greedy/basics-of-greedy-algorithms/practice-problems/algorithm/motu-and-patlu-1-ab612ad8/)

## Question 4: perfect

The square root of a\*a is a and a number is said to be a perfect square if its square root is a positive integer.

Mayank said now I am confident with this topic so Harsh asked him to write a program which can find the nearest perfect square of the entered number and how much steps he should take from the entered number to reach that perfect square. Now you have to help Mayank in writing code.

Input:
The first line contains an integer T, the number of test cases. For each test case, there is an integer n
Output:
For each test case, print the closest perfect square and number of steps required to reach the perfect square

```bash
Example:
Input
2
1500
2
Output
1521 21
1 1
```

[Go to reference](https://practice.geeksforgeeks.org/problems/are-you-perfect/0)

## Question 5: pattern

Given a number N, the task is to print the following pattern:-

```bash
Input :
N = 4

Output :
4 4 4 4 4 4 4
4 3 3 3 3 3 4
4 3 2 2 2 3 4
4 3 2 1 2 3 4
4 3 2 2 2 3 4
4 3 3 3 3 3 4
4 4 4 4 4 4 4

Input :
N = 2

Output :
2 2 2
2 1 2
2 2 2
```

Approach: The common observation is that the square thus formed will be of size (2*N-1)x(2*N-1). Fill the first row and column, last row and column with N, and then gradually decrease N and fill the remaining rows and columns similarly. Decrease N every time after filling 2 rows and 2 columns

[Go to reference](https://www.geeksforgeeks.org/spiral-pattern/)

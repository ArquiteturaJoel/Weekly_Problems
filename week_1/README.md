# Questions : Week 1

## Question 1

Given a square matrix, calculate the absolute difference between the sums of its diagonals.

For example

```bash
  [1  2  3]
  [4  5  6]
  [7  8  9]

  The sum of main diagonal -> 1 + 5 + 9 = 15
  The sum of another diagonal -> 3 + 5 + 7 = 15
  So the absolute difference will be -> |15 - 15| = 0
```

[Go to reference](https://www.hackerrank.com/challenges/diagonal-difference/problem)

## Question 2

Print a right aligned pattern for n like

```bash
   #
  ##
 ###
####
```

where n is 4.

Take input `n` where n stands for the number of line and the number of `#` in last line.

[Go to reference](https://www.hackerrank.com/challenges/staircase/problem)

## Question 3

Given a time in 12-hour AM/PM format, convert it to military (24-hour) time.
Input format will be in `hh:mm:ssAM`.

For example

```bash
05:45:01PM
The answer is 17:45:01
```

[Go to reference](https://www.hackerrank.com/challenges/time-conversion/problem)

## Question 4

Given five positive integers, find the minimum and maximum values that can be calculated by summing exactly four of the five integers. Then print the respective minimum and maximum values as a single line of two space-separated long integers.

For example

```bash
Numbers -> 1 2 3 4 5
Sum w/o 1 -> 2 + 3 + 4 + 5 = 14
Sum w/o 2 -> 1 + 3 + 4 + 5 = 13
Sum w/o 3 -> 1 + 2 + 4 + 5 = 12
Sum w/o 4 -> 1 + 2 + 3 + 5 = 11
Sum w/o 5 -> 1 + 2 + 3 + 4 = 10

Minimum number is -> 10
Maximum number is -> 14
```

[Go to reference](https://www.hackerrank.com/challenges/mini-max-sum/problem)

## Question 5

You are choreographing a circus show with various animals. For one act, you are given two kangaroos on a number line ready to jump in the positive direction (i.e, toward positive infinity).

- The first kangaroo starts at location x1 and moves at a rate of v1 meters per jump.

- The second kangaroo starts at location x2 and moves at a rate of v2 meters per jump.

You have to figure out a way to get both kangaroos at the same location at the same time as part of the show. If it is possible, return YES, otherwise return NO.

For example

```bash
  Input
    x1 = 0
    v1 = 3
    x2 = 4
    v2 = 2

  Output -> YES
```

[Go to reference](https://www.hackerrank.com/challenges/kangaroo/problem)

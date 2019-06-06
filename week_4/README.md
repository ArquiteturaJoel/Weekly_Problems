# Questions : Week 4

## Question 1: gcd

The greatest common divisor `gcd(a, b)` of two non-negative integers a and b
(which are not both equal to 0 ) is the greatest integer d that divides both and b.
Your goal in this problem is to implement the Euclidean algorithm for computing
the greatest common divisor.
Efficient algorithm for computing the greatest common divisor is an important
basic primitive of commonly used cryptographic algorithms like RSA.

**Constraints**: 1 =< a,b =< 2.10^9

```bash
Input:
18 35
Output:
1
```

```bash
Input:
28851538 1183019
Output:
17657
```

Reference will added soon.

## Question 2: lcm

The least common multiple of two positive integers a and b is the least positive
integer m that is divisible by both a and b.

**Constraints**: 1 =< a,b =< 2.10^9

```bash
Input:
6 8
Output:
24
```

```bash
Input:
28851538 1183019
Output:
1933053046
```

Reference will added soon.

## Question 3: fib_again

In this problem, your goal is to compute Fn modulo m, where n may be really huge: up to 10^18. For such
values of n, an algorithm looping for n iterations will not fit into one second for sure. Therefore we need to
avoid such a loop.
To get an idea how to solve this problem without going through all fi for i from 0 to n, let’s see what
happens when m is small — say, m = 2 or m = 3.

| i      | 0   | 1   | 2   | 3   | 4   | 5   | 6   | 7   | 8   | 9   | 10  | 11  | 12  | 13  | 14  | 15  |
| ------ | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| fi     | 0   | 1   | 1   | 2   | 3   | 5   | 8   | 13  | 21  | 34  | 55  | 89  | 144 | 233 | 377 | 610 |
| fimod2 | 0   | 1   | 1   | 0   | 1   | 1   | 0   | 1   | 1   | 0   | 1   | 1   | 0   | 1   | 1   | 0   |
| fimod3 | 0   | 1   | 1   | 2   | 0   | 2   | 2   | 1   | 0   | 1   | 1   | 2   | 0   | 2   | 2   | 1   |

Take a detailed look at this table. Do you see? Both these sequences are periodic! For m = 2, the period
is 011 and has length 3 , while for m = 3 the period is 01120221 and has length 8. Therefore, to compute,
say, f2015 mod 3 we just need to find the remainder of 2015 when divided by 8. Since 2015 = 251·8 + 7, we
conclude that f2015 mod 3 = f7 mod 3 = 1.
This is true in general: for any integer m ≥ 2 , the sequence fn mod m is periodic. The period always
starts with 01 and is known as Pisano period.

```bash
Input:
239 1000
Output:
161
```

```bash
Input:
28851538 1183019
Output:
1933053046
```

Reference will added soon.

## Question 4: last_fib_again

Now, we would like to find the last digit of a partial sum of Fibonacci numbers: fn + fn+1 +···+ fm.

**Constraints**: 1 =< n =< m =< 2.10^18

```bash
Input:
3 7
Output:
1
```

```bash
Input:
10 10
Output:
5
```

Reference will added soon.

## Question 5: money_change

In this problem, you will design and implement an elementary greedy algorithm
used by cashiers all over the world millions of times per day.

Task.The goal in this problem is to find the minimum number of coins needed to change the input value
(an integer) into coins with denominations 1, 5, and 10.

**Constraints**: Input will be less than 104

```bash
Input:
2
Output:
2
```

```bash
Input:
28
Output:
6
```

Reference will added soon.

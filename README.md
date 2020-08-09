Here on earth, our 24-hour day is composed of two parts, each of 12 hours. Each hour in each part has a corresponding hour in the other part separated by 12 hours: the hour essentially measures the duration since the start of the day part. For example, 1 hour in the first part of the day is equivalent to 13, which is 1 hour into the second part of the day.

Now, consider the equivalent hours that are both prime numbers. We have 3 such instances for a 24-hour 2-part day:

5~17

7~19

11~23

Accept two natural numbers D, P >1 corresponding respectively to number of hours per day and number of parts in a day separated by a space. D should be divisible by P, meaning that the number of hours per part (D/P) should be a natural number. Calculate the number of instances of equivalent prime hours. Output zero if there is no such instance. Note that we require each equivalent hour in each part in a day to be a prime number.

Example:

Input: 24 2

Output: 3 (We have 3 instances of equivalent prime hours: 5 ~ 17, 7 ~ 19  and  11 ~ 23.)

Constraints

10 <= D < 500

2 <= P < 50

Input

Single line consists of two space separated integers, D and P corresponding to number of hours per day and number of parts in a day respectively

Output

Output must be a single number, corresponding to the number of instances of equivalent prime number, as described above

Time Limit
1

Examples

Example 1

Input

36 3

Output

2

Explanation

In the given test case D = 36 and P = 3

Duration of each day part = 12

2 ~ 14 ~ X

3 ~ 15 ~ X

5 ~ 17 ~ 29 - instance of equivalent prime hours

7 ~ 19 ~ 31 - instance of equivalent prime hours

11 ~ 23 ~ X

Hence the answers is 2.

Example 2

Input

49 7

Output

0

Explanation

Duration of each day part = 7

2 ~ 9 ~ X ~ 23 ~ X ~ 37 ~ X

3 ~ X ~ 17 ~ X ~ 31 ~ X ~ X

5 ~ X ~ 19 ~ X ~ X ~ X ~ 47

7 ~ X ~ X ~ X ~ X ~ X ~ X

Hence there are no equivalent prime hours.

# Week 02

**DUE ON: 26/9/18 11:59:00 PKT**


You will be submitting the solution on HackerRank and on Github. Moreover, you will also post a screenshot showing the number of test cases you passed on HackerRank.

## Question 01 DONE
[Sherlock and Squares](https://www.hackerrank.com/challenges/sherlock-and-squares/problem)

def squares(a, b):
    count = 0
    for i in range (a,b+1):
        if (math.sqrt(i)).is_integer():
            count= count +1
        else:
            continue
    return count
 

## Question 02
[Encryption](https://www.hackerrank.com/challenges/encryption/problem)

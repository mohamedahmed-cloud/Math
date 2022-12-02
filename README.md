# Math
Math Approach
- ### Number is divisible by 3:
```py
    # to determine if number is divisible by 3 or not
    # sum all digits in number then if the sum is divisible by 3
        # then the number is divible by 3.
        # else not divisible by 3
    n=input()
    sum=0
    for i in n:
        sum+=int(i)
    if sum%3==0:
        print("number is modulus by three")
    else:
        print("number is not modulus by three")
```
----
- ### gcd()
```py
    # gcd(for sum all number from 1 -> n except math.ceil(n/2)    , math.ceil(n/2))>1
    import sys,math,bisect,collections,itertools,heapq
    from collections import defaultdict,deque
    n=int(sys.stdin.readline())
    if n==1 or n==2 : 
        print("No")

    else:
        print("Yes")
        x=math.ceil(n/2)
        print(1,x)
        print(n-1,end=' ')
        for i in range(1,n+1):
            if i!=x:
                print(i,end=' ')

```
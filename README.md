# Math
Math Approach
- Number is divisible by 3:
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

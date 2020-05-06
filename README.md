# Ruby_For_Tester
Ruby Questions and Challenges for Tester

*Question 1:* Write a Ruby program to compute the absolute difference between n and 33 and return double the absolute difference if n is over 33.

```
def diff_33(n)
    n > 33 ? ((n-33)*2).abs : (n-33).abs
end
print diff_33(47),"\n" 
print diff_33(17)
```

*Question 2:*
```
i = [1,2,3,4,5]
i.select {|x| x % 2 == 0}
```

*Question 3:*

```
i = [1,2,3,4,5]
i.map {|x| x+1}
```





```python
s = "A man, a plan, a canal: Panama"
print(len(s))
```

    30



```python
def isPalindrome(s):
    if not s:
        return True
    def f(i):
        q = i.isalpha()
        if 48<= ord(i)<= 57:
            p=1
        else:p=0
        return q or p
    l = list((filter(f,s)))
    s = ''.join(l)
    s = s.upper()
    return s == s[::-1]
```


```python
isPalindrome(s)
```




    True




```python
def isPalindrome(s):
    s = list(str.lower(s))
    L = len(s)
    dic = {}
    if L<=1:
        return True
    for i in s:

            
            
            
```


```python
s[2] != s[1]
```




    True



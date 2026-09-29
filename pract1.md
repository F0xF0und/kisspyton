
##
```

```

## 1 10 чисел
````
a = 42
b = 4
n = 2
c = 42.0

print ('4' + '2' , c, '(', b, n, ')' )
print (4.2e1, 0b101010, 0o52 )
print (4_2, 420e-1, 42e+0)
print (0O52, 0x2a, 42.0000000000000000000000)
````
##
```
x = 10 ** 10000000
print (x)
```
```
x = <int object at 0x00000189E8855040>
Возникло исключение: ValueError
Exceeds the limit (##4300## digits) for integer string conversion; use sys.set_int_max_str_digits() to increase the limit
  File "D:\стол\new\new.py", line 2, in <module>
    print (x)
    ~~~~~~^^^
ValueError: Exceeds the limit (4300 digits) for integer string conversion; use sys.set_int_max_str_digits() to increase the limit
```

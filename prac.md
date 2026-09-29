# zadanie 1.1

```
print(42)
print(0b101010)
print(0o52)
print(0x2A)
print(42.0)
print(4.2e1)
print(6 * 7)
print(40 + 2)
print(84 // 2)
print(42 * 1)
```

# zadanie 1.2

```
import sys
print(sys.maxsize)
print(float('inf'))
print(sys.float_info.max)
```

# zadanie 1.3

```
print(divmod(17, 5))
```

#zadanie 1.4

```
a = 10
while abs(a) > 1e-10:
  a -= 0.1
print(a)
```

# zadanie 1.5

```
Python вычисляет невероятно огромное число, поэтому вычисление занимает очень много времени.
Рабочий код:

z = 1
z <<= 40
print(z)
print(len(str(z)))
```

# zadanie 1.6

```
Операция ++i воспринимается как 2 знака +, поэтому i все время остается равным 0.
Рабочий код:

i = 0
while i < 10:
  print(i)
  i += 1
```

# zadanie 1.7

```
print(True * 2)
print(False + 2)
print(-True)
print((True * 2 + False) * -True)
```

# zadanie 1.8

```
x = 5
print(1 < x < 10)
print(1 < (x < 10))

В 1 принте у нас выдает True, потому что 1 < 5 < 10, это правильно.
Во 2 принте у нас выдает False, потому что идем по порядку скобок: (x < 10) = (5 < 10) --- это правильно(True). А поскольку True = 1, следовательно выражение (1 < (x < 10)) переходит в (1 < 1), что выдает False.
```

# zadanie 2.1

```
if True print('Hello')
```

# zadanie 2.2

```
5 = 10
```

# zadanie 2.3

```
print(x)
```

# zadanie 2.4

```
print('Hello)
```

# zadanie 2.5

```
a = 5
b = '10'
print(a + b)
```

# zadanie 2.6

```
if True:
  print('Hello')
```

# zadanie 2.7

```
if True:
  print('Hello')
    print('World')
```

# zadanie 2.8

```
import math
print(math.sqrt(-1))
```

# zadanie 2.9

```
import math
print(math.exp(1000))
```

# zadaniya 3.1-3.3

```
def a(x):
  x2 = x + x
  x4 = x2 + x2
  x8 = x4 + x4
  return x8 + x4

def b(x):
  x2 = x + x
  x4 = x2 + x2
  x8 = x4 + x4
  x16 = x8 + x8
  return x16

def c(x):
  x2 = x + x
  x4 = x2 + x2
  x8 = x4 + x4
  x16 = x8 + x8
  return x16 - x
```

  

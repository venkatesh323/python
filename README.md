# python
from collections import Counter
s = input()
x = len(s)
m = Counter(s)
a = len(m.keys())
b = len(m.values())
res = a+b
if res<x:
   print("Yes")
else:
   print("No")

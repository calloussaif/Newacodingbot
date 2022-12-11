# Newacodingbot
new repo



import re
str="Example for Meta Characters in Regular Expression"
x=re.findall("e..",str)                           # return any present character expect new character
y=re.findall("a..",str)
z=re.findall("....Exam",str)
t=re.findall("..e",str)
s=re.findall(".e",str)
h=re.findall(".E",str)
l=re.findall("..e..",str)
v=re.findall(" ..",str)
k=re.findall("m*",str)                          #return 0 or more occurances of given char.
m=re.findall("s*",str)
print(x)
print(y)
print(z)
print(t)
print(s)
print(h)
print(l)
print(v)
print(len(str))
print(len(k))
print(len(m))

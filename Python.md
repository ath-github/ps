### PPS practical codes (group of 3)
```python
# Decimal to Octal
# To write a program to find the octal equivalent of the entered number
num=int(input("enter an integer to convert it to its octal equivalent"))
bin=0
p=1
while num!=0:
	d=num%8
	bin=bin+d*p
	p=10*p
	num=num//8
print(bin)
```

```python
# RANGE by Kshitij
n=int(input("enter the number of inputs: "))
a=int(input("enter the first value: "))
b=int(input("enter the second value: "))
if a>=b:
	max=a
else:
	max=b
if a<=b:
	min=a
else:
	min=b
i=3
while i<=n:
	print("for",i,"th value")
	c=int(input("enter the value"))
	if min<=c:
		min=min
	else:
		min=c
	if max>=c:
		max=max
	else:
		max=c
	i=i+1
print("maximum= ",max)
print("minimum= ",min)
range=max-min
print("Range= ",range)
```

## Problem statement - Create flowchart and pseudocode for the following:

### 1. Input a year and find whether it is a leap year or not.

#### Pseudocode

```
start
input year

if year%100 != 0 and year%4 == 0:
  output "leap year"
else if year%400 == 0:
  output "leap year"
else:
  output "not a leap year"

exit
```

#### Flowchart

![image](https://github.com/user-attachments/assets/7db26426-7c45-49c9-9527-a622e5e8ad3d)


### 2. Take two numbers and print the sum of both.

#### Pseudocode 

```
start
input a
input b
sum = a+b
output sum
exit
```

#### Flowchart

![image](https://github.com/user-attachments/assets/2cc819cd-6a65-40e3-9900-5a9e06b3aa71)


### 3. Take a number as input and print the multiplication table for it.

#### Pseudocode

```
start
input num
i = 1
while i <= 10 do:
  output i*n
  i = i+1
exit

```

#### Flowchart

![image](https://github.com/user-attachments/assets/f09771b5-46d9-4b9f-8eaa-0d28d0a70c29)


### 4. Take 2 numbers as inputs and find their HCF and LCM.

#### Pseudocode

```

```

### 5. Keep taking numbers as inputs till the user enters ‘x’, after that print sum of all.

#### Pseudocode

```
start
read x
sum = 0
isX = false
while not(isX):
  input num
  if num == x:
    isX = true
    sum = sum + num
  else:
    sum = sum + num

output sum
exit
```

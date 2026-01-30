# day3-python-loop-statements
 Python loop Statements practice code
# Loop Statements
  # 1 for loop
  # 2 while loop

# Loop Control Statements
  # 1 break statements
  # 2 continue statements
  # 3 pass statements

# for loop
a=10
for i in range(1,10):
    print(i)

# while loop
a=1
while(a<=5):
    print(a)
    a+=1

# Create a User Input

# for loop
a=int(input("Enter a Number :"))
for i in range(1,a+1):
    print(i)

# while loop
x=int(input("Enter a Number :"))
while(x<=5):
    print(x)
    x+=1

# for loop using Break statements

a=10
for i in range(1,10):
    if i==5:
        break   #loop stop here
    print(i)
# for loop using continue statements

b=10
for i in range(1,10):
    if i==5:
        continue    #skip 5
    print(i)
    
 # for loop using Pass statements
c=10
for i in range(1,10):
    if i==5:
        pass   #do nothing
    print(i)
    
# while loop using break statements
a=1
while(a<=10):
    if a==4:
        break
    print(a)
    a+=1

# while loop using continue statements
a=1
while(a<=10):
    if a==4:
        continue
    print(a)
    a+=1

# while loop using pass statements
a=1
while(a<=10):
    if a==4:
        pass
    print(a)
    a+=1

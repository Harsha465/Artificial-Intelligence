x=0
y=0
m=5
n=3
print("initial state = (0,0)")
print("capacities=(5,3)")
print("goal state =(x,y)")
while x!=4:
    r=int(input("enter rule number"))
    if r==1:
        x=m
        print(x,y)
    elif r==2:
        x=0
        print(x,y)
    elif r==3:
        y=n
        print(x,y)
    elif r==4:
        y=0
        print(x,y)
    elif r==5:
        x+=y
        y=0
        print(x,y)
    elif r==6:
        y+=x
        x=0
        print(x,y)

    elif r==7:
        t=m-x
        x=m
        y-=t
        print(x,y)

    elif r==8:
        t=n-y
        y=n
        x-=t
        print(x,y)

print('(',x,',',y,')')
if x==y:
    print("goal state reached : ")

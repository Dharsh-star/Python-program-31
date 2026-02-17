# Python-program-31
4.import datetime
td=0
now=datetime.datetime.now()
print(now.day)
if now.month==2:
    td=28
elif now.month in(1,3,5,7,8,10,12):
    td=31
else:
    td=30
print("Total remaining days in the current month are : ",td-now.day)

Output
4
Total remaining days in the current month are :  27

5.r=int(input("Enter the radius : "))
h=int(input("Enter the height : "))
vol=3.14*r*r*h
print("Volume of the cylinder is : ",vol)

Output:
Enter the radius : 5
Enter the height : 4
Volume of the cylinder is :  314.0

ovpay=0
sum=0
for i in range(1,11):
    print("Enter Working Hours of Emp",i,":")
    h=int(input())
if(h>40):
    extra=h-40
    ovpay=extra*12
    print("Over time pay of emp",i,"is",ovpay)
    sum=sum+ovpay

else:
    print("no Overtime pay")
    print("Total Overtime pay allemployees:",sum)

Output:
Enter Working Hours of Emp 1 :
24
Enter Working Hours of Emp 2 :
8
Enter Working Hours of Emp 3 :
16
Enter Working Hours of Emp 4 :
12
Enter Working Hours of Emp 5 :
48
Enter Working Hours of Emp 6 :
32
Enter Working Hours of Emp 7 :
56
Enter Working Hours of Emp 8 :
34
Enter Working Hours of Emp 9 :
31
Enter Working Hours of Emp 10 :
44
Over time pay of emp 10 is 48


# Finding-the-Second-Largest-Element-in-a-List

a=[]
n=int(input("enter number of elements:"))
for i in range(1,n+1):
    b=int(input("enter element:"))
    a.append(b)
a.sort()
print("second largest element is:",a[n-2])




Output:

enter number of elements:3
enter element:5
enter element:6
enter element:7
second largest element is: 6

# Bubble-Sort
def bs(a):
    for i in range(0,len(a)):
        for j in range(0,len(a)-1):
            if a[j]>a[j+1]:
                a[j],a[j+1]=a[j+1],a[j]
data=[]
n=int(input("How many Inputs are there : "))
for i in range(n):
    x=float(input("enter the Input number " +str(i+1)+" : "))
    data.append(x)
bs(data)
print(data,sep="\n")

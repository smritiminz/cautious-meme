# cautious-meme
def fibo(x):
    if x<=1:
        return x
    else:
       return fibo(x-1)+fibo(x-2)

n= int(input("enter no of terms"))
for i in range(n):
       y=fibo(i)
       print(y,end=" ")
      
l=[0,1]
for i in range (10):
    x=l[-1]+l[-2]
    l=l+[x]
print(l)

def greeting(x):
    print("Hello",x)

l=["john","Aman","ram",]
for i in l:
    greeting(i)

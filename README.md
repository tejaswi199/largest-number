# largest num by user input
#Approach-1
a=int(input())
b=int(input())
if(a>b ):
  print(a,"is largest")
else:
  print(b,"is largest")
#Approach-2
x,y=map(int,input().split())
if(x>y ):
  print(x,"is largest")
else:
  print(y,"is largest")
#Approach-3
q,w=map(int,input().split(","))
if(q>w ):
  print(q,"is largest")
else:
  print(w,"is largest")

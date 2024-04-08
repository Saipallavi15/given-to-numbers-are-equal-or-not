# given-to-numbers-are-equal-or-not
def check(a,b)
if a==b:
return 0
if a>b:
return 1
if a<b:
a=5
b=3
result=check(a,b)
if result==0:
print("a==b")
if result==1:
print("a>b")
if result==-1:print("a<b")



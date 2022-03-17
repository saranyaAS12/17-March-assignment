S=input()
L=list(S)
u=0
l=0
d=0
s=0
p=0
for i in S:
    if(i.isupper()):
        u=u+1
    elif(i.islower()):
        l=l+1
    elif(i.isdigit()):
        d=d+1
    else:
        s=s+1
    if (i=='@' and i=='$'):
        p=p+1
if(u>=1 and l>=1 and d>=1):
    print("valid password")
else:
    print("invalid password")

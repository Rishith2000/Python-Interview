# Python-Interview
s="Good Morning, How are you?"
h=len(s)-1
k=""
for i in range(len(s)-1,0,-1):
    if(i==0):
        k=k+s[i:h+1]
    elif(s[i]==" "):
        k=k+s[i:h+1]
        h=i-1
k=k+" "+s[0:h+1]
print(k)

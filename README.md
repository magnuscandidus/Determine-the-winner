# Determine-the-winner
# cook your dish here
for i in range (int(input())):
    a,b,c,d = map(int,input().split())
    p=max(a,b)
    q=max(c,d)
    if(p<q):
        print("P")
    elif(q<p):
        print("Q")
    else:
        print("TIE")

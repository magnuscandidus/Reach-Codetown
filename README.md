# Reach-Codetown
for i in range(int(input())):
    s=input()
    v=['A','E','I','O','U']
    if s[1] not in v or s[3] not in v or s[5] not in v:
        print("NO")
    elif s[0] in v or s[2] in v or s[4] in v or s[6] in v or s[7] in v:
        print("NO")
    else:
        print("YES")

    
    

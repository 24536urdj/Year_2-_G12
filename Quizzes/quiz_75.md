```.py
def bin(N:str):
    for a in N :
        b = ord(a)
        c = ""
        x=[]
        while b != 0 :
            c = c+str(b%2)
            b = b//2
        if b == 0 :
            c = c+str(b%2)
        for i in range(len(c)-1,-1,-1):
            print(c[i],end="")

```
![Screen Shot 2023-09-09 at 21 53 12](https://github.com/24536urdj/Year_2-_G12/assets/112072887/300bf1c6-e400-46f2-93ef-3fc8f41790cf)


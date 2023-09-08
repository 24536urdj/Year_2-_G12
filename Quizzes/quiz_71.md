```.py
import random


def IPgenerator(N: int):
    x = []
    for i in range(0, 256):

        x.append(i)
        sl = [str(j) for j in x]
        ipv = []
    for f in range(N):
        ip = ""
        for m in range(4):
            ip += sl[random.randint(0,256)]
            ip += "."
        ipv.append(ip[:-1])

    output = ipv
    print(output)

```
![Screen Shot 2023-09-08 at 20 30 29](https://github.com/24536urdj/Year_2-_G12/assets/112072887/221abf7b-ca56-43ae-9a1e-cfde61dfbaca)


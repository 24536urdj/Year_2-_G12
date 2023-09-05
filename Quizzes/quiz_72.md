```.py
import random
def macgenerator(N:int):
    x = ["0","1","2","3","4","5","6","7","8","9","A","B","C","D","E","F"]
    all_macs = []
    for i in range(N):
        mac=""
        for j in range(6):
           for d in range(2):
                mac+= x[random.randint(0,15)]
           mac+= ":"
        all_macs.append(mac[:-1])
    output = all_macs
    return output

macgenerator(3)

```
![Screen Shot 2023-09-05 at 20 08 13](https://github.com/24536urdj/Year_2-_G12/assets/112072887/0e30f1a5-7b36-49f8-9aae-c474cd3c1aba)

```.py
x = [0, 0, 0, 0]
print(x)
for i in range(0, 255):
    c = 0

    for j in range(0,4):


        if j == 0:
            x[3] += 1
        if j == 1:
            x[2] += 1
        if j  == 2:
            x[1] += 1
        if j == 3:
            x[0] += 1

        print(x)

```

```.py
  def error_check(data:str):
      output = True
      d = data
      y = d[0:len(d)//3]
      z = d[len(d)//3:2*len(d)//3]
      w= d[2*len(d)//3:len(d)+1]
      if y == z and z==w :
          output = False
      if y != z or z!= w :
          output = True

    print(output)
```
![Screen Shot 2023-09-08 at 5 52 04](https://github.com/24536urdj/Year_2-_G12/assets/112072887/34974999-8de1-45be-89c0-b918c8d9b485)

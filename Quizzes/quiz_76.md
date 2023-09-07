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

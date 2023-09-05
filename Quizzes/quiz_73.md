```.py
    def build_data_pkg(ms:str,ips:str,mr:str,ipr:str,data:str):
      a = ms.split()
      b=[]
      b.append(a)
      x = []
      y = []
      d = 0
      for i in range(0,len(data),4) :
            c = data[i:i+4]
            header = f"{ms}|{ips}|{mr}|{ipr}|{c}"
            x.append(header)
            d+=1
    
    
      y.append(x)
      return y 
```
![Screen Shot 2023-09-05 at 20 05 31](https://github.com/24536urdj/Year_2-_G12/assets/112072887/b5bb3be1-a765-4432-8cc6-98f6a1df651e)



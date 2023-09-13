```.py
routing_table = {}
last_ip_digit = 1

def macip(mac_add: str):
    global last_ip_digit

    x = []
    for i in mac_add:
        x.append(i)

    if len(x) != 17 or mac_add.count(":") != 5:
        print("Invalid MAC address format.")
        return

    if mac_add in routing_table:
        print(f"MAC address {mac_add} already exists. IP address: {routing_table[mac_add]}")
    else:
        ip_address = f"190.118.1.{last_ip_digit}"
        last_ip_digit += 1
        routing_table[mac_add] = ip_address
        print(f"Added entry: {mac_add} -> {ip_address}")

    print("\nUpdated Routing Table:")
    print("{:<18} {:<15}".format("MAC Address", "IP Address"))
    print("-" * 35)

    for mac, ip in routing_table.items():
        print("{:<18} {:<15}".format(mac, ip))
```
![Screen Shot 2023-09-13 at 22 17 33](https://github.com/24536urdj/Year_2-_G12/assets/112072887/df23eaf5-7c76-4a02-95f2-8862259b42d0)



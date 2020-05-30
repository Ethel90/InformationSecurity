
# __Kali&Win10 CyberSecurity__


## __Install VMware__ ##

Kali : [Click](kali.org/downloads/)

## __open 2 VM(Kali&Win10)__
```
Win10 open cmd -> ipconfig(search your IP location)
Kali open terminal -> sudo su(Get license) -> ifconfig(search your IP location) 
```
- in order to pair two VM , you need to check whether the inet are the same 
```
if not the same, go "Player" get Manage (VM settings) then network adapter. (Often NAT or Bridged would be chosen)
```

## __Lab1__ ##
```
open Kali's BurpSuite -> Proxy (options) -> add specific address(your kali's ip) and set the port number.
After done it, open Win10 
install google chrome -> settings(search proxy) -> open it and input kali's ip and port -> save
```

## __弱點管理__ ##
```
Use Nessus(Free)
fault : Only 16 IP can be detected.

step 1 > Close Proxy setting
step 2 > Set Network Adapter to "Bridge"
step 3 > Go https://localhost:8834 (Work inside VM)
step 4 > Create Policy (new Policies -> Advanced Scan)
Tips: you can adjust in "Performance Options"
```

## __爬網站__ ##
- [Here](https://archive.org)

## __資料提取工具__ ##
- FOCA
```
In Win10-bin -> new Project 
```

## __WireShark__
```
Go Kali-Linux > wireshark
```
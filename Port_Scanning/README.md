# Port Scanning 

```shell
nmap -PN -v -p0-65535 192.168.1.0/24 #Scan all Ports Including 0
``` 

```shell
nmap -PN -v -p0- -T4 192.168.1.0/24 # -p0- same as -p0-65535 , T4 to speed up the scan 
```

<img width="691" alt="Screen Shot 2021-12-29 at 12 03 37" src="https://user-images.githubusercontent.com/92652606/147655805-5dd64688-0933-4750-bc44-eb2a6e6be0a6.png">

* ***Port Scanning Methods***

```shell
-sS # TCP SYN Stealth 
-sT # TCP connect
-sU # UDP 
-sA # TCP ACK 
# -sF , -sX , -sN used sometomes to bypass firewalls
-sF # TCP FIN
-sX # TCP Xmas 
-sN # TCP Null 
-sO # IP protocol scan , used to find out which ip protocol the target are suportted ( tcp , udp , icmp , igmp )

```

```shell
-p 22 # scan just port 22
-p ssh # scan just ssh port ( 22)
-p80-1000 # scan range ports
-pT:22,23,U:53 # scan tcp port 22,23 and udp port 53 

```

<img width="612" alt="Screen Shot 2021-12-29 at 12 28 08" src="https://user-images.githubusercontent.com/92652606/147657705-66e494a7-5e67-4e4e-89dc-834c03bea2e2.png">




















```nmap-services ``` : This file has well-known services for Ports and Protocols .

<img width="794" alt="Screen Shot 2021-12-29 at 11 43 07" src="https://user-images.githubusercontent.com/92652606/147654225-4a4d2917-01d6-415c-9a43-ca5effcf4ac5.png">


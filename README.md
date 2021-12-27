# nmap


* ***Host Discovery ( Ping Scanning )***

```-iL```: read input from a file 

```--exclude``` : Exclude a target you dont want to scan

![Screenshot from 2021-12-27 09-52-54](https://user-images.githubusercontent.com/92652606/147460658-6e09008d-2e55-404f-b22b-34a95b3cc3b2.png)

```-sL``` : List Scan , simply list each host on the network and the scan is stealth 

![Screenshot from 2021-12-27 10-03-18](https://user-images.githubusercontent.com/92652606/147460950-3e3c73e9-ace9-4489-bbab-72589dda73dc.png)

```-sP```: Ping Scan ( USING ICMP ECHO REQUEST )

```-PN``` : disable Ping ( USEFULL when you know ur target is up or against Firewalls )

![Screenshot from 2021-12-27 10-27-18](https://user-images.githubusercontent.com/92652606/147463022-edf6bd5b-87cf-43af-aa6b-507ba449c47e.png)


```-PS<Port numbers>``` : TCP SYN PING : using the syn flag to ping a specific Port .

![Screenshot from 2021-12-27 10-29-37](https://user-images.githubusercontent.com/92652606/147463171-2be81fea-3c21-4324-afa0-32629a26fd92.png)

```-PA<port numbers>```: TCP ACK PING 
  
```-PU<port numbers>```: UDP PING

```-PR``` : ARP Scan 




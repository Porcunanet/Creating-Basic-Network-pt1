# Build a Basic Cisco Network

| Devices
| --- |
ISR4321 R1
ISR4321 R2
3650-24PS Multi Layer Switch  

## _Instructions_

* Change Hostname
```sh
hostname <change name>
```
* Change IP address and Subnet Mask --> Class C
```sh
interface gigabit 0/0/0
ip address 10.1.1.1 255.255.255.0
```

* After IP Interface make sure to input no shutdown
```sh
no shut
```

* Save Configuration 
```sh
do wr
```
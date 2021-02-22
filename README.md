# VLAN Configuration Lab   
Full configuration for my VLAN configuration lab   

### S1
```
interface Vlan10
  description Default gateway for VLAN 10
  mac-address 00d0.d3bc.4301
  ip address 192.168.10.254 255.255.255.0

interface Vlan20
  description Default gateway for VLAN 20
  mac-address 00d0.d3bc.4302
  ip address 192.168.20.254 255.255.255.0

interface Vlan30
  description Default gateway for VLAN 30
  mac-address 00d0.d3bc.4303
  ip address 192.168.30.254 255.255.255.0

interface Vlan40
  description Default gateway for VLAN 40
  mac-address 00d0.d3bc.4304
  ip address 192.168.40.254 255.255.255.0

 interface FastEthernet0/1
  switchport access vlan 10
  switchport mode access
  switchport nonegotiate

 interface FastEthernet0/2
  switchport access vlan 10
  switchport mode access
  switchport nonegotiate

 interface FastEthernet0/3
  switchport access vlan 10
  switchport mode access
  switchport nonegotiate

 interface FastEthernet0/4
  switchport access vlan 10
  switchport mode access
  switchport nonegotiate

 interface FastEthernet0/5
  switchport access vlan 10
  switchport mode access
  switchport nonegotiate

 interface FastEthernet0/6
  switchport access vlan 10
  switchport mode access
  switchport nonegotiate

 interface FastEthernet0/7
  switchport access vlan 20
  switchport mode access
  switchport nonegotiate

 interface FastEthernet0/8
  switchport access vlan 20
  switchport mode access
  switchport nonegotiate

 interface FastEthernet0/9
  switchport access vlan 20
  switchport mode access
  switchport nonegotiate

 interface FastEthernet0/10
  switchport access vlan 20
  switchport mode access
  switchport nonegotiate

 interface FastEthernet0/11
  switchport access vlan 20
  switchport mode access
  switchport nonegotiate

 interface FastEthernet0/12
  switchport access vlan 20
  switchport mode access
  switchport nonegotiate

 interface FastEthernet0/13
  switchport access vlan 30
  switchport mode access
  switchport nonegotiate

 interface FastEthernet0/14
  switchport access vlan 30
  switchport mode access
  switchport nonegotiate

 interface FastEthernet0/15
  switchport access vlan 30
  switchport mode access
  switchport nonegotiate

 interface FastEthernet0/16
  switchport access vlan 30
  switchport mode access
  switchport nonegotiate

 interface FastEthernet0/17
  switchport access vlan 30
  switchport mode access
  switchport nonegotiate

 interface FastEthernet0/18
  switchport access vlan 30
  switchport mode access
  switchport nonegotiate

 interface FastEthernet0/19
  switchport access vlan 40
  switchport mode access
  switchport nonegotiate

 interface FastEthernet0/20
  switchport access vlan 40
  switchport mode access
  switchport nonegotiate

 interface FastEthernet0/21
  switchport access vlan 40
  switchport mode access
  switchport nonegotiate

 interface FastEthernet0/22
  switchport access vlan 40
  switchport mode access
  switchport nonegotiate

 interface FastEthernet0/23
  switchport access vlan 40
  switchport mode access
  switchport nonegotiate

 interface FastEthernet0/24
  switchport access vlan 40
  switchport mode access
  switchport nonegotiate
```

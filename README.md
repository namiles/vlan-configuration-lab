# VLAN Configuration Lab   
Full configuration for my VLAN configuration lab. All of the below command are ran in global config mode.   

### S1
```
vlan 10
  name Administration

vlan 20
  name Accounting

vlan 30
  name Sales

vlan 40
  name Support

interface FastEthernet0/1
  switchport access vlan 10
  switchport mode access

interface FastEthernet0/2
  switchport access vlan 10
  switchport mode access

interface FastEthernet0/3
  switchport access vlan 10
  switchport mode access

interface FastEthernet0/4
  switchport access vlan 10
  switchport mode access

interface FastEthernet0/5
  switchport access vlan 10
  switchport mode access

interface FastEthernet0/6
  switchport access vlan 10
  switchport mode access

interface FastEthernet0/7
  switchport access vlan 20
  switchport mode access

interface FastEthernet0/8
  switchport access vlan 20
  switchport mode access

interface FastEthernet0/9
  switchport access vlan 20
  switchport mode access

interface FastEthernet0/10
  switchport access vlan 20
  switchport mode access

interface FastEthernet0/11
  switchport access vlan 20
  switchport mode access

interface FastEthernet0/12
  switchport access vlan 20
  switchport mode access

interface FastEthernet0/13
  switchport access vlan 30
  switchport mode access

interface FastEthernet0/14
  switchport access vlan 30
  switchport mode access

interface FastEthernet0/15
  switchport access vlan 30
  switchport mode access

interface FastEthernet0/16
  switchport access vlan 30
  switchport mode access

interface FastEthernet0/17
  switchport access vlan 30
  switchport mode access
  
interface FastEthernet0/18
  switchport access vlan 30
  switchport mode access

interface FastEthernet0/19
  switchport access vlan 40
  switchport mode access

interface FastEthernet0/20
  switchport access vlan 40
  switchport mode access

interface FastEthernet0/21
  switchport access vlan 40
  switchport mode access

interface FastEthernet0/22
  switchport access vlan 40
  switchport mode access

interface FastEthernet0/23
  switchport access vlan 40
  switchport mode access

interface FastEthernet0/24
  switchport access vlan 40
  switchport mode access
```

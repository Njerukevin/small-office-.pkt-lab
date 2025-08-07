# small-office-.pkt-lab
In this project, I configured a multi-switch Cisco topology running DHCP and OSPF as the main IGP.

📌Tasks performed

1) Erased startup configs for a clean setup on all devices
2) came up with an IP addressing scheme
3) configured static trunk links between the switches
4) Created VLANS on the switches
   vlan 10
   vlan 20
   vlan 30
   vlan 40
5)configured STP PORTFAST on all switches with the DEFAULT command
6) The main office router is configured with ROAS and acts as a DHCP Relay agent for the vlans
7) There's one standard ACL on the ISP 1 router that denies communication from all ISP2 addresses

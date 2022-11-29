# pt_project
I put most I've learned from CCNA in this project, the designing might not suit in real world scenario due to my lack of experience,   
Summary of the topology:
-Port security, ip DHCP snooping and ARP inspection configured on all switches 
-OSPF configured all all routers and multi-layer switches
-Dynamic PAT configured on Router 5, forming the ip address to port translation 
-ACL applied on MSW 1, the rules is to deny traffics from other vlans to vlan 30 - Law department 
-MSW 1 was getting DHCP and DNS from server within it's network; MSW 2 has it's own DHCP pool and providing DHCP service to vlans within it's network
-WAN configured in MSW 2 network, providing internal and guest basic sevice set
 **the version of packet tracer i'm currently using got bug on WLC configuration, SVI address and related vlans all set and the PC for WLC GUI configuration can actually ping with WLC ip address, but the HTTPS service to GUI doesn't work properly.**

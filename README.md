# Ether-channel
Etherchannel
------------

SW-1
int range fa0/1-3
channel-group 1 mode auto

trunk
---------
int port-channel 1
switchport mode trunk

SW-2
int range fa0/1-3
channel-group 2 mode desirable

trunk
---------
int port-channel 2
switchport mode trunk

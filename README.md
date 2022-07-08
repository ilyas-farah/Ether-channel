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
![spanning tree](https://user-images.githubusercontent.com/106605770/177991366-3dbbc651-d177-4e4a-9005-340c1a214605.jpg)

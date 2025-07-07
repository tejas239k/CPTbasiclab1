# CPTbasiclab1
This is my first basic CPT lab uploading on GitHub for documentation purpose and future use.

Here I have setup a pc, a switch and a router 
and I'm trying to ping router from pc.

R1 configuration
enable
configure terminal
hostname R1
interface fa0/0 
ip address 192.168.1.1 255.255.255.0
no shutdown

NOTE: "no shutdown" command is mandatory!!

In PC
Manual configuration
IPv4 Address 192.168.1.2
Subnet Mask 255.255.255.0
Default Gateway 192.168.1.1

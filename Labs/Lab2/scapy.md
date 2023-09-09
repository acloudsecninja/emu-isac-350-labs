# scapy lab with Kali Linux

- Scapy is a powerful python-based interaction packet maniuplation program and libary.

In this lab you will use scapy to show various packets to the pfsense and to kali linux!

Github repo --> https://github.com/secdev/scapy

Enjoy!

-Ryan

# How to Install and sent the packet for this lab!

1. pip install scapy

2. x = IP(ttl=64) - press enter

# Not a real IP address in the Network
3. x.src="192.168.41.123" - press enter

# pfsense new network router
4. x.dst="192.168.41.3" - [press enter]

5. lsc() and then sent(x) - press enter

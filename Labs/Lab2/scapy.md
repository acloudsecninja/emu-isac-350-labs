# ISAC 350- Lab 2 - Scapy Lab With Kali Linux

- Scapy is a powerful python-based interaction packet maniuplation program and libary.

In this lab you will use scapy to show various packets to the pfsense and to kali linux!

Github repo --> https://github.com/secdev/scapy

Enjoy!

-Ryan

# How to Install and sent the packets for this lab!

Step 1

```bash
pip install scapy
```
Step 2

```bash
x = IP(ttl=64) - press enter
```

Step 3

```bash
x.src="192.168.41.123"
```

Step 4

```bash
x.dst="192.168.41.3"
```

Step 5

```bash
EXAMPLE --> send(IP(src="192.168.41.123" , dst="192.168.41.3")/TCP(sport=80,dport=80) , count=2000)
```

Step 6

The next step is to enable diagnostic in your pfsense so you can caputre this for the video upload.

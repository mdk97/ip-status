# ip-status

Makes it easier to see the IP configuration on a Unix-like system with a text formatting imitating the ipconfig on Windows machines.

### No more suffering with _ip a_

With ip-status you can see all the IP addresses at once on a simple and organized way.

## Example output
```
Ethernet interface: lo

IPv4 . . . . . . . . . . : 127.0.0.1
IPv6 . . . . . . . . . . : ::1

Ethernet interface: enp8s0

IPv4 . . . . . . . . . . : 200.9.84.74
IPv6 . . . . . . . . . . : 2801:b0:b0:112:c908:81c8:891d:eee7

Wireless interface: wlp14s0

Not connected . . . . . . . . . . : skipping

Ethernet interface: docker0

IPv4 . . . . . . . . . . : 172.17.0.1
IPv6 . . . . . . . . . . : 172.17.0.1
```
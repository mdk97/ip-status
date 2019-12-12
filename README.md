# ip-status

Makes it easier to see the IP configuration on Linux systems that have support for the `ip` command.
Prints formatted text imitating the ipconfig command on Windows machines.

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
```
## Dependencies

It doesn't require any dependencies as it's just a Perl script that parses the _ip a_ command output.

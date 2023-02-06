# pcap-strip

The best way to learn about the Internet is to focus on that part, ignoring the
local network. This tool read a *pcap* file and strips out the local Ethernet
information. This means stripping out things that are purely Ethernet, like
bridging protocols and ARP. It also means stripping out anything before the IP
header.


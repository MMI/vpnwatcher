# vpnwatcher

**Description**

A simple shell script to watch a VPN connection. When the VPN
connection is down, it will stop uTorrent (by sending SIGSTOP). When
the VPN connection comes back up, it will resume uTorrent (by sending
SIGCONT).

## Details

* Developed and testing on MacOS 10.12
* assumes VPN up/down based on the presence of a ppp0 interface
* cycles every 5 seconds

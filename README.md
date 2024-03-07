# Writeup

## Conocer la red

Lo primero de todos es encontrar equipos dentro de mi red.

`sudo arp-scan -I eth0 --localnet`

`Interface: eth0, type: EN10MB, MAC: 00:0c:29:59:a3:11, IPv4: 192.168.95.103
Starting arp-scan 1.10.0 with 256 hosts (https://github.com/royhills/arp-scan)
192.168.95.100  3c:7c:3f:ed:f7:dd       ASUSTek COMPUTER INC.
192.168.95.104  00:0c:29:1d:a1:79       VMware, Inc.
192.168.95.117  a2:17:1c:66:78:ec       (Unknown: locally administered)
192.168.95.208  b4:b0:24:39:35:08       TP-Link Corporation Limited

4 packets received by filter, 0 packets dropped by kernel
Ending arp-scan 1.10.0: 256 hosts scanned in 2.026 seconds (126.36 hosts/sec). 4 responded`

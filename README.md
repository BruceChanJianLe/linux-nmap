# Linux nmap

This repository demonstrate the use of nmap.

## Installation

```
# Debian/Ubuntu
sudo apt-get install nmap
# CentOS/Redhat
yum install nmap
```

## Usage

1. To scan a System with Hostname and IP address. First, Scan using Hostname 

```
nmap www.google.com
```

2. Check all available ip address on a network

```
nmap -sP 192.168.10.0/24
```

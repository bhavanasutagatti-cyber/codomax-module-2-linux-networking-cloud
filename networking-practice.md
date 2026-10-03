# Networking Practice – Codomax Module 2

## Overview

This document contains my practical networking exercises completed
for Codomax Module 2: Linux, Networking & Cloud Infrastructure.

I practiced networking commands using an online Ubuntu/Linux environment.

---

## 1. IP Addressing

### Commands Used

```bash
ip addr
hostname -I
ip link
ip route
ping -c 4 8.8.8.8

cat /etc/resolv.conf
getent hosts google.com
nslookup google.com
dig google.com
getent hosts example.com
ping -c 4 example.com

ss -tuln
ss -tulpn
sudo ss -tulpn
ss -tuln | grep ':22'

sudo ufw status
sudo ufw allow 22/tcp
sudo ufw enable
sudo ufw status
sudo ufw allow 80/tcp
sudo ufw status
sudo ufw delete allow 80/tcp
sudo ufw status


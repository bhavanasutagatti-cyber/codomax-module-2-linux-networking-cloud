# Linux Practice – Codomax Module 2

## Overview

This document contains my practical Linux work completed for
Codomax Module 2: Linux, Networking & Cloud Infrastructure.

I practiced Linux commands using an online Ubuntu/Linux environment.

---

## 1. Linux CLI Operations

### Commands Used

```bash
pwd
ls
mkdir module2-practice
cd module2-practice
touch test.txt
echo "Linux CLI practice" > test.txt
cat test.txt
ls -l

touch permissions.txt
ls -l permissions.txt
echo "Module 2 permissions practice" > permissions.txt
chmod 600 permissions.txt
ls -l permissions.txt
chmod 644 permissions.txt
ls -l permissions.txt

whoami
id
cat /etc/passwd
sudo useradd -m moduleuser
id moduleuser
sudo groupadd modulegroup
sudo usermod -aG modulegroup moduleuser
groups moduleuser
grep moduleuser /etc/passwd

ps
ps aux
top

sleep 300 &
ps aux | grep sleep
kill PID
ps aux | grep sleep

sudo systemctl status ssh
sudo systemctl start ssh
sudo systemctl stop ssh
sudo systemctl restart ssh
sudo systemctl enable ssh
sudo systemctl disable ssh
systemctl is-enabled ssh
systemctl is-active ssh

ls -la ~/.ssh
mkdir -p ~/.ssh
chmod 700 ~/.ssh
ssh-keygen -t ed25519 -C "module2-practice"
ls -la ~/.ssh
cat ~/.ssh/id_ed25519.pub
ssh-keygen -lf ~/.ssh/id_ed25519.pub


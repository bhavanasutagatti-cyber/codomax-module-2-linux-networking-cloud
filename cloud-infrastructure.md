# Cloud Infrastructure – Codomax Module 2

## Overview

This document records my learning and exploration of cloud infrastructure
concepts for Codomax Module 2: Linux, Networking & Cloud Infrastructure.

## Cloud Platform

AWS

## Virtual Machines

A cloud virtual machine provides computing resources such as:

- CPU
- Memory
- Storage
- Operating system
- Network connectivity

AWS EC2 provides virtual servers that can run Linux operating systems.

## Linux Configuration

A Linux cloud server can be configured using:

- Command-line tools
- Users and groups
- File permissions
- Services
- SSH
- Firewall rules

The Linux administration commands practiced in this module are documented
in `linux-practice.md`.

## Secure Access

SSH can be used to securely access a Linux server remotely.

SSH keys provide authentication using:

- Public key
- Private key

The private key must be kept secure and must never be shared publicly.

## Network Security

Cloud resources can use security controls such as AWS Security Groups.

Security Groups can control network traffic based on:

- Protocol
- Port
- Source or destination

Common ports include:

| Port | Protocol | Purpose |
|------|----------|---------|
| 22 | SSH | Secure remote administration |
| 80 | HTTP | Web traffic |
| 443 | HTTPS | Secure web traffic |

## Service Deployment

A Linux cloud server can host services such as web applications.

A typical deployment process is:

1. Create a virtual machine.
2. Configure the Linux operating system.
3. Configure secure access.
4. Install the required service.
5. Configure network access.
6. Test connectivity.

## Connectivity Testing

Connectivity can be tested using Linux networking commands such as:

```bash
ping
ss
ip addr
ip route



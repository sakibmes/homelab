# Lab 3: Proxmox Homelab

Converted a used $100 Dell OptiPlex into a dedicated Type 1 hypervisor running Proxmox VE.

## Overview
- Verified the Proxmox ISO via SHA256 hashing before install
- Configured BIOS virtualization (VT-x, VT-d) and disabled Secure Boot
- Installed Proxmox VE and set a static IP for headless web management
- Resolved a repository authentication (401) error by switching from the enterprise repo to the no-subscription repo via the Linux CLI

## Tools
Proxmox VE, Linux CLI, virtualization

## Full write-up
[Read on Medium](https://medium.com/@mes.sakib)

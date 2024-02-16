---
title: NFS
pubDate: 16-02-2024
---
# Network File System

## Server

### Debian

#### Installing the NFS server

```sh
sudo apt install nfs-kernel-server
```

#### Configuring the NFS export

```sh
sudo vi /etc/exports
# /media *(rw,sync,no_subtree_check)
```
- Shares the /media folder to all IP addresses (*)
- Allows users to read, write, sync, and enable better performance by disabling subtree checks.

## Client

### MacOS

Commands are a little different compared to Linux clients. Was a bit frustrated trying to set this up so here are the commands in case I need to reference it again.

```sh
sudo mount_nfs -o resvport <server_ip_addr>:/media /Volumes/media
```
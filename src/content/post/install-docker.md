---
title: "Install Docker on Raspberry Pi"
description: "Learn how to install Docker on your Raspberry Pi to run containerized applications and services."
publishDate: "6 Feb 2025"
# updatedDate: 6 December 2024
tags: ["raspberry-pi", "linux", "self-host"]
---

## Overview

Docker is a powerful containerization tool that simplifies software deployment by packaging applications and their dependencies into containers. This guide provides a step-by-step process to install Docker on a Linux system.

## Installation Steps

### Step 1: Update System Packages

Before installing Docker, ensure your system is up to date:

```bash
sudo apt update
sudo apt upgrade
```

### Step 2: Install Docker

Run the following command to download and install Docker:

```bash
curl -sSL https://get.docker.com | sh
```

### Step 3: Install User ID Mapping Tools

Docker rootless mode requires `newuidmap` and `newgidmap` binaries:

```bash
sudo sh -eux <<EOF
# Install newuidmap & newgidmap binaries
apt-get install -y uidmap
EOF
```

### Step 4: Set Up Rootless Docker

Enable rootless mode with the following command:

```bash
dockerd-rootless-setuptool.sh install
```

### Step 5: Install Docker Compose

Docker Compose allows you to manage multi-container applications. Install it with:

```bash
sudo apt install docker-compose-plugin
```

### Step 6: Verify Installation

Check the installed Docker and Docker Compose versions:

```bash
docker --version
docker compose version
```

## Conclusion

You have successfully installed Docker and Docker Compose on your Linux system. You can now start using containers to develop and deploy applications efficiently. For further configurations, refer to the official Docker documentation.

## Full Script

```bash
sudo apt update
sudo apt upgrade

curl -sSL https://get.docker.com | sh

sudo sh -eux <<EOF
# Install newuidmap & newgidmap binaries
apt-get install -y uidmap
EOF

dockerd-rootless-setuptool.sh install

sudo apt install docker-compose-plugin

docker --version
docker compose version
```

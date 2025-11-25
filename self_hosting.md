
# 🧬 Self-Hosted Services Overview

This repository provides an overview of a privacy-focused, self-hosted Home LAN infrastructure.
The goal is to replace common cloud-based services with secure, reliable, locally controlled solutions.
Each application runs in either a **Virtual Machine (VM)** or an **LXC Container**, depending on isolation and performance requirements.

---

## 📸 Photo & Media Management

### **Self-Hosted Photo Library**

**Software:** Immich
**Type:** LXC Container
**Description:** A high-performance alternative to Google Photos for storing, organizing, and backing up photos and videos. Supports auto-upload, face recognition, and albums.
🔗 [https://immich.app/](https://immich.app/)

---

### **Media Streaming Server**

**Software:** Jellyfin
**Type:** LXC Container
**Description:** Open-source media server for streaming movies, TV shows, and personal videos across local devices.
🔗 [https://jellyfin.org/](https://jellyfin.org/)

---

### **Music Streaming Server**

**Software:** Navidrome
**Type:** LXC Container
**Description:** Lightweight server for streaming a personal music library. Compatible with Subsonic clients on mobile and desktop.
🔗 [https://www.navidrome.org/](https://www.navidrome.org/)

---

## 🌐 Networking & Web Access

### **Reverse Proxy & SSL Management**

**Software:** Nginx Proxy Manager
**Type:** LXC Container
**Description:** Intuitive interface for managing reverse proxies, HTTPS certificates, and secure access to internal services.
🔗 [https://nginxproxymanager.com/](https://nginxproxymanager.com/)

---

### **Network-Wide Ad Blocking & DNS**

**Software:** Pi-hole
**Type:** LXC Container
**Description:** DNS-based ad-blocking for the entire network, filtering ads, tracking domains, and malicious hosts.
🔗 [https://pi-hole.net/](https://pi-hole.net/)

---

### **VPN for Remote Access**

**Software:** WireGuard
**Type:** Runs on Mikrotik (native service)
**Description:** Modern, fast, secure VPN protocol enabling encrypted and private access to the Home LAN from anywhere.
🔗 [https://www.wireguard.com/](https://www.wireguard.com/)

---

## 🏠 Home Automation

### **Home Automation Platform**

**Software:** Home Assistant
**Type:** Virtual Machine
**Description:** Controls smart home devices, sensors, voice interactions, and automations with an extensive plugin ecosystem.
🔗 [https://www.home-assistant.io/](https://www.home-assistant.io/)

---

## 🗂️ File Sync, Documents & Personal Data

### **File Sync & Personal Drive**

**Software:** Seafile
**Type:** LXC Container
**Description:** Enterprise-grade file synchronization and collaboration, similar to Dropbox or Google Drive.
🔗 [https://www.seafile.com/](https://www.seafile.com/)

---

### **Calendar & Contacts Server**

**Software:** Radicale
**Type:** LXC Container
**Description:** Lightweight CalDAV/CardDAV server for calendars and address books.
🔗 [https://radicale.org/](https://radicale.org/)

---

### **Peer-to-Peer File Synchronization**

**Software:** Syncthing
**Type:** LXC Container
**Description:** Secure, decentralized file synchronization between devices with no central server.
🔗 [https://syncthing.net/](https://syncthing.net/)

---

## 📰 News, Feeds & Knowledge

### **RSS Feed Aggregator**

**Software:** FreshRSS
**Type:** LXC Container
**Description:** Web-based RSS reader for consolidating news, blogs, and updates in one place.
🔗 [https://www.freshrss.org/](https://www.freshrss.org/)

---

### **Bookmarking & Link Archiving**

**Software:** Linkding
**Type:** LXC Container
**Description:** Minimalist, fast bookmark manager for saving, tagging, and organizing links.
🔗 [https://github.com/sissbruecker/linkding](https://github.com/sissbruecker/linkding)

---

## 🧠 Knowledge & Notes

### **Personal Knowledge Base**

**Software:** Trilium Notes
**Type:** LXC Container
**Description:** A powerful hierarchical note-taking platform supporting rich text, scripting, relations, and structured knowledge management. Ideal for personal wikis, research notes, and long-term knowledge archiving.
🔗 [https://github.com/zadam/trilium](https://github.com/zadam/trilium)

---

## 📊 Monitoring & Performance

### **Home Server Monitoring Dashboard**

**Software:** Beszel
**Type:** LXC Container
**Description:** Lightweight, self-hosted dashboard for monitoring CPU, RAM, storage, and network usage across multiple machines. Ideal for tracking resource consumption in the Home LAN.
🔗 [https://github.com/henrygd/beszel](https://github.com/henrygd/beszel)

---

## 🔐 Backup & Storage

### **Backup Server**

**Software:** Proxmox Backup Server
**Type:** Virtual Machine
**Description:** Encrypted, deduplicated, incremental backups for VMs, containers, and datasets.
🔗 [https://www.proxmox.com/en/proxmox-backup-server](https://www.proxmox.com/en/proxmox-backup-server)

---

### **Encrypted Incremental Backups (Offsite + Local)**

**Software:** Borg + Borgmatic + BorgBase
**Type:** CLI tools (host-level)
**Description:**
A robust backup solution using Borg for deduplicated, encrypted backups, orchestrated with Borgmatic for automation and policies.
Backups are sent both **locally** and **offsite** to BorgBase, providing full disaster recovery with minimal storage footprint.
Ideal for configuration files, datasets, and long-term storage.

🔗 [https://www.borgbackup.org/](https://www.borgbackup.org/)
🔗 [https://torsion.org/borgmatic/](https://torsion.org/borgmatic/)
🔗 [https://www.borgbase.com/](https://www.borgbase.com/)

---



# 🧬 Self-Hosted Services Overview

This repository provides an overview of a privacy-focused, self-hosted Home LAN infrastructure.  
The goal is to replace common cloud-based services with secure, reliable, locally controlled solutions.  
Each application runs in either a **Virtual Machine (VM)** or an **LXC Container**, depending on isolation and performance requirements.

---

## 📚 Table of Contents

- [Photo & Media Management](#-photo--media-management)
- [Networking & Web Access](#-networking--web-access)
- [Home Automation](#-home-automation)
- [File Sync, Documents & Personal Data](#️-file-sync-documents--personal-data)
- [News, Feeds & Knowledge](#-news-feeds--knowledge)
- [Backup & Storage](#-backup--storage)
- [Bitcoin & Lightning](#-bitcoin--lightning)

---

## 📸 Photo & Media Management

### **Self-Hosted Photo Library**  
**Software:** Immich  
**Type:** LXC Container or Virtual Machine  
**Description:** A high-performance alternative to Google Photos for storing, organizing, and backing up photos and videos. Supports auto-upload, face recognition, and albums.  
🔗 https://immich.app/

---

### **Media Streaming Server**  
**Software:** Jellyfin  
**Type:** LXC Container or Virtual Machine  
**Description:** An open-source media server for streaming movies, TV shows, and personal videos across local devices.  
🔗 https://jellyfin.org/

---

### **Music Streaming Server**  
**Software:** Navidrome  
**Type:** LXC Container or Virtual Machine  
**Description:** A lightweight server for streaming your personal music library. Compatible with Subsonic clients on mobile and desktop.  
🔗 https://www.navidrome.org/

---

## 🌐 Networking & Web Access

### **Reverse Proxy & SSL Management**  
**Software:** Nginx Proxy Manager  
**Type:** LXC Container or Virtual Machine  
**Description:** Provides an intuitive interface for managing reverse proxies, HTTPS certificates, and secure access to internal services.  
🔗 https://nginxproxymanager.com/

---

### **Network-Wide Ad Blocking & DNS**  
**Software:** Pi-hole  
**Type:** LXC Container or Virtual Machine  
**Description:** A DNS-based ad-blocking solution that filters ads, tracking domains, and malicious sites for every device on the network.  
🔗 https://pi-hole.net/

---

### **VPN for Remote Access**  
**Software:** WireGuard  
**Type:** VM or LXC Container  
**Description:** A modern, fast, secure VPN protocol enabling encrypted and private access to the Home LAN from anywhere.  
🔗 https://www.wireguard.com/

---

## 🏠 Home Automation

### **Home Automation Platform**  
**Software:** Home Assistant  
**Type:** Virtual Machine  
**Description:** Controls and automates smart home devices, sensors, voice interactions, and custom automations with an extensive plugin ecosystem.  
🔗 https://www.home-assistant.io/

---

## 🗂️ File Sync, Documents & Personal Data

### **File Sync & Personal Drive**  
**Software:** Seafile  
**Type:** LXC Container or Virtual Machine  
**Description:** High-performance, enterprise-grade file synchronization and collaboration, similar to Dropbox or Google Drive.  
🔗 https://www.seafile.com/

---

### **Calendar & Contacts Server**  
**Software:** Radicale  
**Type:** LXC Container or Virtual Machine  
**Description:** A simple, lightweight CalDAV/CardDAV server for syncing calendars and address books across devices.  
🔗 https://radicale.org/

---

### **Peer-to-Peer File Synchronization**  
**Software:** Syncthing  
**Type:** LXC Container or Virtual Machine  
**Description:** Secure, decentralized file synchronization between devices with no central server required. Ideal for backups and collaborative folders.  
🔗 https://syncthing.net/

---

## 📰 News, Feeds & Knowledge

### **RSS Feed Aggregator**  
**Software:** FreshRSS  
**Type:** LXC Container or Virtual Machine  
**Description:** A lightweight web-based RSS reader for consolidating news, blogs, and updates in a single interface.  
🔗 https://www.freshrss.org/

---

### **Bookmarking & Link Archiving**  
**Software:** Linkding  
**Type:** LXC Container or Virtual Machine  
**Description:** A minimalist, fast, self-hosted bookmark manager for saving, tagging, and organizing links.  
🔗 https://github.com/sissbruecker/linkding

---

## 🔐 Backup & Storage

### **Backup Server**  
**Software:** Proxmox Backup Server  
**Type:** Virtual Machine  
**Description:** Provides encrypted, deduplicated, incremental backups for virtual machines, containers, and datasets. Ensures fast, reliable restores.  
🔗 https://www.proxmox.com/en/proxmox-backup-server

---

### **Encrypted Deduplicated Backups**  
**Software:** Duplicacy  
**Type:** Can run as CLI tool or in a container  
**Description:** Efficient deduplication and encryption for backing up folders or datasets to local or offsite storage.  
🔗 https://duplicacy.com/

---

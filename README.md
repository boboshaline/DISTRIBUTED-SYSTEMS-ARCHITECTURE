# Distributed Systems Architectures: Netflix & BitTorrent

## Overview
This repository contains a report on two major distributed system architectures: **Netflix** (multi-tier with edge caching) and **BitTorrent** (pure peer-to-peer). The report includes:

- ASCII diagrams illustrating each architecture  
- Explanations of how each system handles **load**, **failure**, and **scaling**  

This work is based on concepts from distributed systems, including client-server, peer-to-peer, multi-tier systems, and edge caching strategies.

---

## Included Files
- `Distributed_Systems_Architecture.pdf` – The main PDF report including diagrams and explanations.  

---

## Architectures Covered

### 1. Netflix (Multi-tier + Edge Caching)
- Uses multi-tier architecture separating presentation, application logic, and data storage  
- Edge caching (CDN nodes) reduces latency and server load  
- Load, failure, and scaling are managed through caching, redundant servers, and horizontal scaling  

### 2. BitTorrent (Pure P2P)
- Decentralized peer-to-peer network where all peers share file pieces  
- Tracker or DHT helps peers discover each other  
- Load is distributed among peers, failure is mitigated through redundancy, and scaling is automatic as more peers join  

---

## How to View
Open `Distributed_Systems_Report.pdf` using any standard PDF viewer, such as:  
- Adobe Acrobat Reader  
- Google Chrome PDF Viewer  
- Microsoft Edge  
- Preview (Mac)  

---

## Author
**Shaline Wambui**  
**Course/Assignment:** Distributed Systems Coursework  

---

## License
This repository is for academic purposes. All content is original and created for the assignment.

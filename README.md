# 👥 Identity-Verified Global Chat

A scalable, asynchronous communication platform that prioritizes authenticity. By integrating real-time photo verification, the system ensures a human-only environment, effectively eliminating bots and fraudulent accounts.

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python)
![Database](https://img.shields.io/badge/SQL-PostgreSQL%2FSQLite-blue?style=for-the-badge&logo=postgresql)
![Async](https://img.shields.io/badge/Asynchronous-Asyncio-orange?style=for-the-badge)
![Deployment](https://img.shields.io/badge/Deployment-Ubuntu%20VPS-green?style=for-the-badge&logo=ubuntu)

## 🌟 Overview

This project is a high-load chat application designed to connect people in a unified space where every user is verified. Unlike traditional anonymous chats, this platform requires face-identity verification to guarantee that every participant is a real person.



## 🚀 Technical Features

### ⚡ High-Load & Scalability
- **Asynchronous Architecture:** Built using `asyncio` to handle thousands of concurrent requests without blocking the main thread.
- **Scalable Core:** The codebase is optimized for horizontal scaling, allowing easy migration from a single VPS to a cluster environment.

### 🛡️ Identity Verification & Anti-Bot System
- **Face Recognition Integration:** Every user session is tied to a verified face photo, ensuring 1:1 identity mapping.
- **Local Data Analysis:** User metadata is stored and analyzed in real-time to detect suspicious patterns and automatically blacklist bots.
- **Auto-Ban Logic:** A dedicated module monitors activity logs to prevent spam and unauthorized access.

### 📊 Data Management
- **SQL-Based Storage:** Utilizes a structured SQL database to ensure data integrity, ACID compliance, and fast query execution for large datasets.
- **Organized Storage:** File-based indexing for rapid retrieval of verification assets.

## 🏗️ Deployment
The service is currently optimized for **Ubuntu VPS** environments, providing full control over the request lifecycle and system resources. 

- **Low-Latency:** Configured to handle requests efficiently even under hardware constraints.
- **Process Control:** Custom monitoring scripts to ensure 99.9% uptime.

## 🛠️ Tech Stack
- **Backend:** Python (Asyncio, Aiohttp/FastAPI)
- **Database:** SQL (PostgreSQL/SQLite)
- **Environment:** Ubuntu Linux
- **Verification:** Custom Computer Vision / Image Processing logic

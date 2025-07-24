# Nextcloud LAN HTTPS Security Demo

A secure, self-hosted Nextcloud server configured to run over HTTPS within a local network (LAN).  
This project is part of my home lab, designed to enhance my skills in Linux server administration, networking, and cybersecurity.

---

## 🚀 Features

- 📂 Private file hosting and sharing with Nextcloud
- 🔐 HTTPS secured via self-signed certificate or LAN-compatible CA
- 🧱 Firewall rules and port restrictions for LAN-only access
- 👥 Multi-user support with group-based permissions
- 📸 Step-by-step visual guide with screenshots

---

## 📸 Step-by-Step Screenshots

A full walkthrough of the setup and usage process.

### 1. Starting the Docker Stack
![Startup](screenshots/insecure-server.png)

---

### 2. Accessing the Web Interface (HTTPS in Browser)
![HTTPS Access](screenshots/02-https-browser.png)

---

### 3. Nextcloud Initial Setup Screen
![Nextcloud Setup](screenshots/03-nextcloud-setup.png)

---

### 4. Creating Admin Account
![Admin Account Creation](screenshots/04-create-admin.png)

---

### 5. Nextcloud Dashboard After Login
![Dashboard](screenshots/05-dashboard.png)

---

### 6. Uploading Files
![File Upload](screenshots/06-upload-file.png)

---

### 7. Enforcing HTTPS in Browser
![HTTPS Lock Icon](screenshots/07-https-lock.png)

---

### 8. UFW Firewall Rules Active
![Firewall Rules](screenshots/08-ufw.png)

---

## 🛠️ Technologies Used

- **Ubuntu Server 24.04**
- **Docker & Docker Compose**
- **Nextcloud (latest)**
- **Nginx (reverse proxy)**
- **OpenSSL (self-signed certs)**


---

## 🔐 Security Summary

- HTTPS enforced with local certificates
- Removed default credentials after setup
- System hardened as part of cybersecurity practice

---

## 📚 How to Deploy

1. Clone the repository:
   ```bash
   git clone https://github.com/romulo-feitosa/nextcloud-lan-https-security-demo.git
   cd nextcloud-lan-https-security-demo

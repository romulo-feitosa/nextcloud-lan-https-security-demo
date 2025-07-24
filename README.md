# Nextcloud LAN HTTPS Security Demo

A secure, self-hosted Nextcloud server configured to run over HTTPS within a local network (LAN).  
This project is part of my home lab, designed to enhance my skills in Linux server administration, networking, and cybersecurity.

---

## 🚀 Features

- 📂 Private file hosting and sharing with Nextcloud
- 🔐 HTTPS secured via self-signed certificate or LAN-compatible CA
- 📸 Step-by-step visual guide with screenshots

---

## 📸 Step-by-Step Screenshots

A full walkthrough of the setup and usage process.

### 1. Updating system Packages
![Update](screenshots/update-packages.png)

### 2. Downloading NextCloud
![Download](screenshots/download-nextcloud.png)

### 3. Moving NextCloud Folder
![Moving NextCloud Folder](screenshots/moving-nextcloud-folder.png)

### 4. Installing Apache, Maria and PHP extensions
![Apache, Mariadb and PHP extensions](screenshots/apache-mariadb-extensions-installation.png)

### 5. Configuring NextCloud database (Mariadb)
![Download](screenshots/nextcloud-database.png)

### 6. Setting Permissions
![Download](screenshots/setting-permissions.png)

### 7. Creating Apache configuration 
![Apache configuration file](screenshots/creating-apache-configuration-file.png)

### 8. Enabling Apache modules and site
![Enabling Apache modules and site](screenshots/enabling-apache-modules-and-site.png)




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

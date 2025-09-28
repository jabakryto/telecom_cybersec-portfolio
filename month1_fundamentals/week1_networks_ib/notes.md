# Week 1: Networks & Cybersecurity Fundamentals
## 📡 Networking Basics
### OSI Model (7 layers)
1. **Physical** – кабели, сигналы, биты  
2. **Data Link** – MAC-адреса, коммутация (Ethernet, Wi-Fi)  
3. **Network** – IP-адресация, маршрутизация (IPv4, ICMP)  
4. **Transport** – сегментация, надёжность (TCP, UDP)  
5. **Session** – управление сессиями  
6. **Presentation** – кодирование, шифрование  
7. **Application** – HTTP, DNS, FTP
### IP Addressing
- **IP**: `192.0.2.10` (RFC 5737 — для документации)
- **Gateway**: `192.0.2.1`
- **DNS**: `8.8.8.8`
- **Ports**: 22 (SSH), 80 (HTTP), 443 (HTTPS)
## 🔒 Cybersecurity Fundamentals
### CIA Triad
- **Confidentiality**, **Integrity**, **Availability**
### OWASP Top 10
- Injection, Broken Auth, XSS, SSRF, Security Misconfig
### Attacks
- **DDoS**, **MITM**, **Phishing**, **Brute Force**
## 🐧 Linux Basics
- `/etc` – configs
- `/var/log` – logs
- `grep`, `cat`, `ls`, `chmod` – essential commands
# Week 1: Networks & Cybersecurity Fundamentals
## 📡 Networking Basics
### OSI Model (7 layers)
1. **Physical** – кабели, сигналы, биты  
2. **Data Link** – MAC-адреса, коммутация (Ethernet, Wi-Fi)  
3. **Network** – IP-адресация, маршрутизация (IPv4, ICMP)  
4. **Transport** – сегментация, надёжность (TCP, UDP)  
5. **Session** – управление сессиями  
6. **Presentation** – кодирование, шифрование  
7. **Application** – HTTP, DNS, FTP

### IP Addressing & Key Concepts
- **IP-адрес**: `192.0.2.10` (RFC 5737 — для документации)
- **Маска подсети**: `255.255.255.0` → `/24`
- **Шлюз**: `192.0.2.1`
- **DNS**: `8.8.8.8`
- **Порты**:  
  - `22` – SSH  
  - `80` – HTTP  
  - `443` – HTTPS  
  - `53` – DNS

## 🔒 Cybersecurity Fundamentals
### CIA Triad
- **Confidentiality** – данные доступны только авторизованным  
- **Integrity** – данные не искажены  
- **Availability** – система доступна при необходимости

### OWASP Top 10 (2021)
1. Broken Access Control  
2. Cryptographic Failures  
3. Injection (SQLi, Command)  
4. Insecure Design  
5. Security Misconfiguration  
6. Vulnerable Components  
7. Authentication Failures  
8. Software Integrity Failures  
9. Logging Failures  
10. SSRF

### Common Attacks
- **DDoS** – перегрузка ресурсов  
- **MITM** – перехват трафика  
- **Phishing** – социальная инженерия  
- **Brute Force** – перебор паролей

## 🐧 Linux Basics
- `/etc` – конфигурации  
- `/var/log` – системные логи  
- `/home` – пользовательские файлы  
- Команды: `ls`, `cd`, `cat`, `grep`, `chmod`, `ps`

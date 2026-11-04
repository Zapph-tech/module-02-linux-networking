# Module 02: Linux, Networking & Cloud Infrastructure

## 1. Linux CLI & Networking Notes
- **CLI Commands:** `ls`, `cd`, `pwd`, `chmod 400`, `systemctl start/stop`
- **Ports:** 22 (SSH), 80 (HTTP)
- **Security Groups:** Act as a stateful firewall at the instance level.

## 2. Deployment Walkthrough
1. **Created VM:** Launched EC2 (Amazon Linux) in eu-north-1.
2. **Secured Access:** Allowed SSH (Port 22) from My IP and HTTP (Port 80) from anywhere.
3. **Configured Linux:** Updated packages and installed Apache (`sudo yum install httpd -y`).
4. **Deployed Service:** Started Apache and wrote a test `index.html` file.
5. **Tested Connectivity:** Verified the webpage loaded successfully via the Public IP.

## 3. Proof of Work
<img width="2287" height="1167" alt="Screenshot From 2026-11-03 21-58-22" src="https://github.com/user-attachments/assets/7143abd1-7b8d-4c52-819f-6cc04a6aa8a3" />
<img width="2287" height="1110" alt="Screenshot From 2026-11-03 22-00-26" src="https://github.com/user-attachments/assets/0d2f1447-dc00-4748-b57d-a78bec4bcc6a" />
<img width="1642" height="750" alt="Screenshot From 2026-11-03 22-08-40" src="https://github.com/user-attachments/assets/949347a7-2525-4d2a-a078-31db4661acca" />
<img width="1912" height="1074" alt="Screenshot From 2026-11-03 22-08-55" src="https://github.com/user-attachments/assets/8ae185a5-2e20-46e0-861f-9aaf23d90f68" />
<img width="1912" height="1074" alt="Screenshot From 2026-11-03 22-09-06" src="https://github.com/user-attachments/assets/d547fa1e-dbba-4294-858f-1d555350ccee" />
<img width="1912" height="1074" alt="Screenshot From 2026-11-03 22-09-15" src="https://github.com/user-attachments/assets/d322f941-ef32-4cc6-9051-faee13c69770" />
<img width="2293" height="1110" alt="Screenshot From 2026-11-03 22-12-58" src="https://github.com/user-attachments/assets/50f962ad-999c-458e-ab78-10579586cbd7" />

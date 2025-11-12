# Linux Shell Assignment

## Project Overview
This repository contains three functional **Bash shell scripts** created as part of the Linux coursework.  
Each script demonstrates automation and system management tasks commonly used by Linux users and system administrators.

**Repository Name:** `linux-shell-assignment`  
**Author:** [Rohit Singh]
**Roll Number:** [2501060098]
**Date:** [14 November 2025]  

---

## Included Scripts

| Script Name | Description | Key Features |
|--------------|--------------|---------------|
| `backup_directory.sh` | Creates a backup of a specified directory with a timestamp. | Uses `tar` for compression, includes timestamp for versioning. |
| `system_monitor.sh` | Logs CPU and memory usage at regular intervals. | Utilizes `top` and `free` commands to track performance metrics. |
| `auto_download.sh` | Automatically downloads files from the internet. | Uses `wget` to download files into a predefined directory. |


## Instructions for Running the Scripts

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/<rohitrksingh1920>/linux-shell-assignment.git
cd linux-shell-assignment
```

### 2️⃣ Make Scripts Executable
Before running, ensure each script has execute permission:
```bash
chmod +x backup_directory.sh system_monitor.sh auto_download.sh
```

### 3️⃣ Run Each Script

#### a) Backup a Directory
```bash
./backup_directory.sh
```
Creates a compressed backup of a specified folder and stores it in the backup directory with a timestamp.

---

#### b) CPU/Memory Monitoring
```bash
./system_monitor.sh
```
Logs CPU and memory usage into `system_usage.log` every few seconds (default: 10 seconds).  
Press `Ctrl + C` to stop monitoring.


#### c) Automated Download Task
```bash
./auto_download.sh
```
Downloads a file from the internet (using `wget`) and saves it in the `Downloads` directory.


## Script Descriptions (Brief)

### 1. backup_directory.sh
- **Purpose:** Automates directory backup and compression.  
- **Tools Used:** `tar`, `date`, and directory creation commands.  
- **Use Case:** Data protection and versioned backups.

### 2. system_monitor.sh
- **Purpose:** Logs real-time CPU and RAM usage.  
- **Tools Used:** `top`, `free`, `grep`, and loops.  
- **Use Case:** Server performance monitoring and troubleshooting.

### 3. auto_download.sh
- **Purpose:** Downloads files from specified URLs automatically.  
- **Tools Used:** `wget`, `curl`, and conditional statements.  
- **Use Case:** Automate routine downloads (e.g., reports or backups).<img width="1840" height="1080" alt="Screenshot (237)" src="https://github.com/user-attachments/assets/5e60b2b1-e4cd-4208-a02e-99bb258193ae" />
<img width="1828" height="1080" alt="Screenshot (236)" src="https://github.com/user-attachments/assets/8ddd9597-e546-46ce-b361-fc38cfc40c9f" />
<img width="1920" height="1080" alt="Screenshot (235)" src="https://github.com/user-attachments/assets/587f5b11-65a7-498b-9af2-b93b60e100aa" />
<img width="1845" height="1080" alt="Screenshot (234)" src="https://github.com/user-attachments/assets/dce82908-8008-4c9c-9bf1-a04cfdace8e5" />
<img width="1840" height="1080" alt="Screenshot (233)" src="https://github.com/user-attachments/assets/972cd579-ebec-416b-ac6c-7ae5590cb8d0" />
<img width="1840" height="1080" alt="Screenshot (232)" src="https://github.com/user-attachments/assets/f132046b-691e-40d1-9867-af8ca13dfbaa" />
<img width="1840" height="1080" alt="Screenshot (231)" src="https://github.com/user-attachments/assets/aff51bb9-aeec-4637-aac5-e2e6a2521685" />
<img width="1845" height="1080" alt="Screenshot (230)" src="https://github.com/user-attachments/assets/0f53486b-fbdd-48be-bdd0-27ccd20ea54b" />
<img width="1836" height="1080" alt="Screenshot (229)" src="https://github.com/user-attachments/assets/cd9b836b-454e-408b-acc4-701f77403ff3" />
<img width="1849" height="1080" alt="Screenshot (228)" src="https://github.com/user-attachments/assets/b2a9afcc-0a50-4327-b59b-2f2637d1e754" />
<img width="1840" height="1080" alt="Screenshot (227)" src="https://github.com/user-attachments/assets/6eb182ae-38b5-4989-9a9f-7cd902a533c0" />
<img width="1840" height="1080" alt="Screenshot (226)" src="https://github.com/user-attachments/assets/70971591-b57c-487d-bdfa-ffa958563e58" />
<img width="1845" height="1080" alt="Screenshot (225)" src="https://github.com/user-attachments/assets/12ae12f9-d314-404e-bbd8-3aff8a8c0964" />
<img width="1840" height="1080" alt="Screenshot (224)" src="https://github.com/user-attachments/assets/a10dd118-48ea-45b1-b67d-829303a3d8d2" />
<img width="1849" height="1080" alt="Screenshot (223)" src="https://github.com/user-attachments/assets/32b588b6-a499-4b7d-979f-104eb79b5e53" />
<img width="1838" height="1080" alt="Screenshot (222)" src="https://github.com/user-attachments/assets/e23b1ace-d776-475a-82af-45b1c3a890d6" />
<img width="1836" height="1080" alt="Screenshot (221)" src="https://github.com/user-attachments/assets/47dddbef-3fc7-4242-9a3c-d9cc0892d25f" />
<img width="1832" height="1080" alt="Screenshot (220)" src="https://github.com/user-attachments/assets/57ae6b37-25f1-4b76-9eb0-3babcb5cf91f" />
<img width="1845" height="1080" alt="Screenshot (219)" src="https://github.com/user-attachments/assets/aac82660-daa1-4b15-a327-04251f9b90ca" />
<img width="1834" height="1080" alt="Screenshot (218)" src="https://github.com/user-attachments/assets/d5051780-28ea-4ad1-a653-aeae205ada7d" />
<img width="1836" height="1080" alt="Screenshot (217)" src="https://github.com/user-attachments/assets/227b3852-f983-4684-affa-2524aa3054e0" />
<img width="1840" height="1080" alt="Screenshot (216)" src="https://github.com/user-attachments/assets/a989cfc3-5433-4738-958f-620df2525dd9" />
<img width="1845" height="1080" alt="Screenshot (215)" src="https://github.com/user-attachments/assets/8aeb2091-fdc1-4760-9b95-3a66366f611d" />
<img width="1832" height="1080" alt="Screenshot (214)" src="https://github.com/user-attachments/assets/669f92ee-4311-478a-a2fe-3ca2fe090179" />
<img width="1836" height="1080" alt="Screenshot (213)" src="https://github.com/user-attachments/assets/ee08033c-ea26-4fdd-842b-c8d0d8b47307" />
<img width="1828" height="1080" alt="Screenshot (212)" src="https://github.com/user-attachments/assets/65bb499c-0e9f-443d-9a98-e07688c3f94b" />
<img width="1824" height="1080" alt="Screenshot (211)" src="https://github.com/user-attachments/assets/d67ad8a9-e592-49ad-a8c7-d54964f32feb" />
<img width="1840" height="1080" alt="Screenshot (207)" src="https://github.com/user-attachments/assets/8bfd1a98-d395-401b-9a53-39246637bd4f" />
<img width="1920" height="876" alt="Screenshot (204)" src="https://github.com/user-attachments/assets/0d6b521d-94c3-492d-8a00-44c5242f7e9c" />
<img width="1920" height="871" alt="Screenshot (203)" src="https://github.com/user-attachments/assets/a653d039-8f23-46de-b6ea-a60ef32335d8" />

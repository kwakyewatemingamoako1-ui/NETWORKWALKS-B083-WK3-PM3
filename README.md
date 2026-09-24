<div align="center">

## 🔐 PASSWORD SECURITY & HASH CRACKING

 Building an authorized and controlled testing framework for ethical hacking and password auditing practice.

</div>

  <p align="center">
  <img src="https://img.shields.io/badge/Skill-Cybersecurity-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/OS-Windows%20PC-0070C0?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Tool-John%20the%20Ripper-E87500?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Tool-Johnny%20GUI-238F89?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Task-Password%20Cracking-C00000?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Skill-Hash%20Extraction-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/Type-Dictionary%20Attack-0070C0?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Target-Encrypted%20PDF-E87500?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/GitHub-Repository-404040?style=flat-square&labelColor=0070C0&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/NetworkWalks-Academy-C00000?style=flat-square&labelColor=000000" />
  <img src="https://img.shields.io/badge/Ethical%20Hacking-E87500?style=flat-square&labelColor=000000" />
</p>  

<br> 

---

<br>

## 📂 1. PROJECT OVERVIEW


This repository documents my practical lab work for **Week 3** covering **Project Modules 1 and 2**.

The primary objective across both modules was to recover the passwords of encrypted PDF files using two different approaches: a local command-line environment and a browser-based utility toolkit.

### 🪟 W3-PM1: Password Cracking with John the Ripper (JTR)

* **Environment:** Windows PC 💻
* **Tools:** John the Ripper (JTR) & Johnny GUI 🕵️‍♂️
* **Overview:** Extracted crackable hashes from protected PDF files, performed a high-speed dictionary attack to recover the original passwords, and verified the results by successfully unlocking and opening the documents 🔓.

### 🌐 W3-PM2: Password Cracking with Networkwalks Tools

* **Environment:** Browser-based 🌍
* **Tools:** Networkwalks Hash Calculator & Password Cracker 🛠️
* **Overview:** Utilized zero-install, web-based utilities to replicate hash-extraction and dictionary-attack logic, successfully recovering file passwords and validating access on the fly ✨.

---
<br>

## 🛡️ 2. Introduction

Welcome to the documentation for my **Week 3** practical project with the Networkwalks Cybersecurity internship. This week explored password security mechanics, cryptographic hashing, file protection, and auditing methodologies.

The practical lab was divided into two distinct approaches:

* **Module 1 (Local Tooling):** Leveraging **John the Ripper (JTR)** and the **Johnny GUI** on a Windows PC to extract PDF hashes, perform dictionary-based recovery, and verify access.
* **Module 2 (Web Utilities):** Utilizing browser-based **Networkwalks** tools to achieve the same hash-extraction and password-cracking workflow with zero local installation.

### 🔄 Project Workflows at a Glance

| Module 01: Local Toolchain | Module 02: Web Toolchain |
| --- | --- |
| 🛠️ **JTR + Johnny GUI** (Windows PC) | 🌐 **Networkwalks Hash Calculator** |
| 📂 **PDF Hash Extraction** | 📂 **PDF Hash Extraction** |
| 🔑 **Password Recovery (Dictionary Attack)** | 🔓 **Networkwalks Password Cracker** |
| ✅ **PDF Verification & Unlocking** | ✨ **Password Recovery & Verification** |

Beyond technical execution, a core focus of this assignment was capturing clear, professional evidence to document every phase of the security auditing process.

Here is a clean, professional, and visually engaging rephrasing of your objectives, formatted with bullet points and emojis for your GitHub README:

---
<br>

## 🎯 3. Objectives

The primary objectives of the Week 3 practical labs were designed to build foundational competency in password auditing and file security:

* 🧠 **Core Concepts:** Master password security fundamentals, cryptographic hashing mechanisms, and how files are protected.

* 🛠️ **Local Tooling (JTR):** Set up and utilize **John the Ripper (JTR)** alongside the **Johnny GUI** interface on a Windows PC.

* 📂 **Hash Operations:** Safely extract, save, and handle password hashes from encrypted PDF files.

* 🌐 **Web-Based Auditing:** Explore zero-install security testing using the **Networkwalks Hash Calculator** and **Password Cracker**.

* 🔓 **Password Recovery:** Execute controlled, authorized dictionary attacks to recover unknown passwords.

* ✅ **Verification:** Test and validate recovered credentials against the target PDF to ensure successful decryption.

* 📝 **Documentation & Evidence:** Capture clear technical evidence and produce professional cybersecurity documentation.

* 🔒 **Security Awareness:** Understand the real-world implications of weak passwords and the necessity for robust defense strategies.


---
<br>

## 🏗️ 4. Lab Architecture & Execution Flow

The lab is structured around a centralized workflow. Whether using local or web-based tooling, every exercise follows the same core security auditing pipeline:

### 🔄 Standardized Workflow Pipeline

1. **Target Acquisition:** Obtain the authorized, password-protected PDF document.

2. **Hash Extraction:** Isolate the cryptographic hash string from the file headers/structure.

3. **Execution & Cracking:** Subject the hash to a dictionary attack using the selected toolkit.

4. **Verification & Proof:** Unlock the document using the recovered password and capture visual evidence.

### 🛠️ Dual-Path Tooling Matrix

| Phase | Module 01 (Local Environment) | Module 02 (Web-Based Environment) |
| --- | --- | --- |
| **Primary Tool** | John the Ripper (JTR) + Johnny GUI | Networkwalks Hash Calculator & Password Cracker |
| **Environment** | Windows PC (Local Execution) | Browser-Based (Zero-Install Utility) |
| **Input** | Encrypted PDF File | Encrypted PDF File |
| **Process** | Local Hash Parsing & Dictionary Attack | Web Utility Hash Extraction & Online Attack Simulation |
| **Output** | Recovered Plaintext Password | Recovered Plaintext Password |
| **Final Step** | Document Unlocking & Evidence Logging | Document Unlocking & Evidence Logging |

<br>

## 💻 5. Module 01 — Windows-Based Password Cracking via John the Ripper

Here is a clean, professional rephrasing of your text, perfectly formatted for your GitHub README:

---

John the Ripper (JTR) is a widely trusted tool for testing password strength, while Johnny provides an intuitive graphical user interface (GUI) for it. The objective of this module was to extract hashes from three protected practice PDFs, crack their passwords using a dictionary attack, and successfully open the files to verify the results.

### 🛠️ Tools Used

* **John the Ripper (Jumbo):** Powerful command-line password auditing tool.
* **Johnny:** Graphical front-end interface for John the Ripper.
* **Online PDF Hash Extractor:** Web utility used to safely extract the required hashes from the target PDFs ([Access Tool](https://www.onlinehashcrack.com/tools-pdf-hash-extractor.php?utm_source=gemini)).

## 📋 Step 1.

Set Up and Verify John (CLI)

<br>

<img width="1887" height="911" alt="Screenshot 2026-09-23 215845" src="https://github.com/user-attachments/assets/c1c27143-c5d0-4d8e-af7e-a2c73af8fab5" />

## 📋 Step 2.

Open Johnny (GUI): Launch the Johnny graphical interface. Ensure it is linked to a valid John the Ripper executable so it can correctly detect and report the version.

<img width="1917" height="1011" alt="Screenshot 2026-09-23 185755" src="https://github.com/user-attachments/assets/ce015036-71ee-4fbc-a6d4-fd60d1f3e579" />


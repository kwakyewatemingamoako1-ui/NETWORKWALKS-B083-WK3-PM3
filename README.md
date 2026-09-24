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

John the Ripper (JTR) is a widely trusted tool for testing password strength, while Johnny provides an intuitive graphical user interface (GUI) for it. The objective of this module was to extract hashes from three protected practice PDFs, crack their passwords using a dictionary attack, and successfully open the files to verify the results.

### 🛠️ Tools Used

* **John the Ripper (Jumbo):** Powerful command-line password auditing tool.
* **Johnny:** Graphical front-end interface for John the Ripper.
* **Online PDF Hash Extractor:** Web utility used to safely extract the required hashes from the target PDFs ([Access Tool](https://www.onlinehashcrack.com/tools-pdf-hash-extractor.php?utm_source=gemini)).

## 📋 Step 1.

**Set Up and Verify John (CLI)**

<br>

<p align="center">
  <img src="https://github.com/user-attachments/assets/c1c27143-c5d0-4d8e-af7e-a2c73af8fab5" alt="John the Ripper Download Page" width="750" style="max-width: 100%;"/>
</p>

<br>

## 📋 Step 2.


* **Open Johnny (GUI):** 

Launch the Johnny graphical interface. Ensure it is linked to a valid John the Ripper executable so it can correctly detect and report the version.

<p align="center">
  <img src="https://github.com/user-attachments/assets/ce015036-71ee-4fbc-a6d4-fd60d1f3e579" alt="Johnny GUI Password Cracking Progress" width="750" style="max-width: 100%;"/>
</p>

Locate and select the `john.exe` executable from your local John the Ripper runtime directory.

<br>

## 📋 Step 3.

* **Extract the PDF Password Hash:**

Upload each locked PDF to the [Online PDF Hash Extractor] (https://www.onlinehashcrack.com/tools-pdf-hash-extractor.php?utm_source=gemini). Ensure the resulting hash string starts with `$pdf$` (stripping any leading `b'` prefix if present) and save each individual hash into separate text files (`hash1.txt`, `hash2.txt`, `hash3.txt`).

<p align="center">
<img src="https://github.com/user-attachments/assets/51448733-6a7c-4398-87c6-e8ca3a0277f6" alt="image" width="750" style="max-width: 100%;"/>
</p>

<p align="center">
<img src="https://github.com/user-attachments/assets/6c467413-fbd8-467b-86e3-8637e27bd59b" alt="image" width="750" style="max-width: 100%;"/>
</p>

<br>

## 📋 Step 4.

* **Execute the Password Attack:**

Launch the cracking process within Johnny by opening your prepared password file and initiating a new attack session.

<p align="center">
  <img src="https://github.com/user-attachments/assets/bd3a8bee-9d5c-46d9-993c-ea6a8bcb1534" alt="Johnny GUI Configuration and Cracking Results" width="750" style="max-width: 100%;"/>
</p>
PDF 1 Result: Successfully recovered the password (`password1`).

<p align="center">
  <img src="https://github.com/user-attachments/assets/bcd5f475-75be-4ea4-a4ff-bbe2edef4217" alt="Lab Results and Verification" width="750" style="max-width: 100%;"/>
</p>
PDF 2 Result: Successfully recovered the password (`password1`).

<p align="center">
  <img src="https://github.com/user-attachments/assets/aeae3b5a-98e7-4fbd-a5b4-83e69122a83e" alt="Lab Completion and Results" width="750" style="max-width: 100%;"/>
</p>
PDF 3 Result: Successfully recovered the password (`1qaz2wsx`).

<br><br>

## 📋 Step 5.

* **Verify and Test Decryption:**

Open each unlocked PDF file to confirm the recovered passwords are correct. Verify that every target document successfully opens, noting that PDF 3 reveals the final lab flag.

<p align="center">
  <img src="https://github.com/user-attachments/assets/99b8d41b-4422-4246-9aa7-f090ef5116d3" alt="Lab Screenshot 1" width="32%">
  &nbsp; &nbsp;
  <img src="https://github.com/user-attachments/assets/0baa1d44-2ed3-41c3-82c4-d896ae331ca5" alt="Lab Screenshot 2" width="32%">
  &nbsp; &nbsp;
  <img src="https://github.com/user-attachments/assets/0868180b-fb67-405e-8a15-25c8309cded3" alt="Lab Screenshot 3" width="32%">
</p>
Successful Decryption: Verified that all three encrypted PDF files open correctly with the plain text passwords discovered during the attack.

<br>

### 📊 Cracking Results & Vulnerability Analysis

| PDF File | Recovered Password | Vulnerability Analysis |
| --- | --- | --- |
| **`My Locked PDF1.pdf`** | `password1` | Highly common default password frequently found in wordlists |
| **`My Locked PDF2.pdf`** | `password1` | Highly common default password frequently found in wordlists |
| **`My Locked PDF3.pdf`** | `1qaz2wsx` | Predictable keyboard-walk pattern making it susceptible to pattern-based cracking |

---

<br>

## 💻 6. Module 02 — Password Cracking with NetworkWalks Online Tools

This alternative module achieves the same objective using zero-installation, browser-based utilities provided by NetworkWalks. By employing two sequential tools, it demonstrates that simple web-based utilities utilize the exact same foundational dictionary-attack principles as John the Ripper.

### 🛠️ Tools Utilized:

* **NetworkWalks Hash Calculator:** Locally parses the locked PDF within the browser to extract the crackable hash.
* **NetworkWalks Password Cracker:** Executes a dictionary attack by hashing each entry in a wordlist and matching it against the extracted PDF hash.

## 🚀 Step 1.

* **Download the Target PDF:**

Access the lab task page and download the locked practice PDF file to serve as the target for the cracking exercise.
<p align="center">
  <img src="https://github.com/user-attachments/assets/12bba646-2e90-4e85-bef6-8efa7cb690e9" alt="Lab Task Setup and Download" width="750" style="max-width: 100%;"/>
</p>
PM2 Lab Task: Online Password Cracking Using NetworkWalks Utilities

## Step 2.

* **Extracting the Target Hash:**

Access the Hash Calculator's PDF tool, upload your locked file, and capture the generated hash details (Revision R4, Version V4, 128-bit key) automatically parsed from the document's encryption structure.

<p align="center">
  <img src="https://github.com/user-attachments/assets/1588ea74-98b1-41bf-8f5e-98892bb93cb2" alt="NetworkWalks Hash Calculator Output" width="750" style="max-width: 100%;"/>
</p>
The Hash Calculator successfully isolates and extracts the target hash from the locked PDF document.

## Step 3.

* **Execute the Dictionary Attack:**

Paste the extracted hash into the Password Cracker and initiate the process. The utility systematically tests each candidate word from the built-in wordlist until a matching key is identified.
<p align="center">
  <img src="https://github.com/user-attachments/assets/3fa54f52-ec99-42ad-b71c-fca1feaad84c" alt="NetworkWalks Password Cracker Execution" width="750" style="max-width: 100%;"/>
</p>

Dictionary Attack Result: The cracking process successfully matched the target hash, recovering the plain text password: `password1`. 

## Step 4.

* **Verify and Test Decryption:**

Open the unlocked PDF file using the recovered password to confirm its validity and reveal the final lab flag.
<p align="center">
  <img src="https://github.com/user-attachments/assets/c1d5e4cd-a7e3-4eb7-bce5-2530d90e3569" alt="Lab Verification and Results" width="750" style="max-width: 100%;"/>
</p>
Final Result: The PDF was successfully unlocked using password1, resulting in the successful capture of the flag.

### 📊 Browser-Based Cracking Results

| PDF File | Recovered Password | Cracking Method |
| --- | --- | --- |
| **`My Locked PDF1.pdf`** | `password1` | Dictionary attack utilizing NetworkWalks built-in wordlist |

<br>

## 🔍 Module Comparison:

| Category | Module 1: John the Ripper | Module 2: NetworkWalks Tools |
| --- | --- | --- |
| **Primary Tool** | John the Ripper (JTR) | NetworkWalks Password Cracker |
| **Interface** | Johnny GUI | Web Browser |
| **Hash Extraction** | Standard PDF hash extraction workflow `$pdf$...` | NetworkWalks Hash Calculator `$pdf$...` |
| **Target** | Protected PDF | Protected PDF |
| **Hash Format** | Standard PDF hash format | Browser-parsed PDF hash format |
| **Environment** | Local Windows System | Web Browser Client-Side |
| **Recovery Process** | Local JTR-based wordlist evaluation | Online NetworkWalks cracking utility |
| **Verification** | Open protected PDF | Open protected PDF |
| **Evidence** | Supporting screenshots | Supporting screenshots |

<br>

## 🧠 Key Learning Outcomes:

* **PDF Hash Extraction:** Learned how to convert a password-protected PDF's encryption metadata into a crackable hash format using both command-line utilities (`pdf2john`) and browser-based alternatives (NetworkWalks Hash Calculator).

* **Dictionary-Based Attacks:** Observed firsthand how password crackers evaluate candidate entries from a wordlist sequentially against a target hash until a match is found, highlighting how rapidly weak credentials fail.

* **CLI vs. Browser-Based Tools:** Gained practical exposure to two distinct interfaces for the same underlying cryptographic concept, contrasting a terminal-driven workflow with a visual, real-time web application.

* **Password Security:** Reinforced a core security principle regarding credential strength; common or predictable passwords fall almost instantly to basic dictionary attacks, whereas long, complex passphrases drastically increase the computational effort required for recovery.

<br>

## Security Recommendations:

* **1️⃣ Enforce Strong Credentials:** Passwords must be lengthy, unique, and resistant to predictive analysis.

* **2️⃣ Prevent Password Reuse:** Users should refrain from utilizing identical credentials across multiple platforms or services.

* **3️⃣ Leverage Password Managers:** Utilize password managers to generate, manage, and securely store complex unique credentials.

* **4️⃣ Enable Multi-Factor Authentication (MFA):** Implement MFA wherever available to introduce an extra layer of defense beyond single-factor passwords.

* **5️⃣ Safeguard Password Hashes:** Securely protect password-related information and restrict unauthorized access to sensitive credential databases.

* **6️⃣ Modernize Storage Mechanisms:** Production environments should implement robust password hashing and key-stretching functions instead of plaintext storage.

* **7️⃣ Conduct Periodic Security Audits:** Organizations must regularly assess password security through authorized evaluation protocols.

* **8️⃣ Track Credential Exposure:** Monitor systems continuously for leaked or compromised credentials and respond swiftly when breaches are suspected.

* **9️⃣ Maintain Documentation:** Ensure security assessments keep thorough, transparent records detailing project scope, methodologies, findings, and results.

* **🔟 Ensure Proper Authorization:** All password security evaluations and penetration testing must strictly adhere to predefined and approved boundaries.

<br>

## Troubleshooting & Challenges:

* **Incorrect Hash Type:** Standard file-hashing utilities initially generated generic checksums (MD5, SHA, CRC). These represent file fingerprints rather than the specialized PDF encryption hash required for decryption attempts; standard file checksums cannot be used to recover a password.

* **Hash Formatting Requirements:** Extracted hashes occasionally included a leading `b'` prefix. This artifact had to be removed to ensure the hash string formatted correctly with the required `$pdf$` prefix, enabling the cracking tool to parse the target successfully.

Here is a polished and professional way to format your disclaimer for your GitHub README:

### ⚠️ Disclaimer

> All files, passwords, and flags utilized in this project belong strictly to a controlled NetworkWalks training lab and are shared for educational and academic purposes only.
>

<br>

## 👤 Author

* **Kwakyewa Teming-Amoako**
* **Cybersecurity Professional B083**
* **LinkedIn:** [Profile Link] *(https://www.linkedin.com/public-profile/settings/?trk=d_flagship3_profile_self_view_public_profile&lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base%3B7M1seD37Qc%2BXe8iGtTBzlQ%3D%3D)*


## 📌 Project Information

* **Program Name:** Cybersecurity at NetworkWalks
* **Week:** 03
* **Project:** Password Cracking
* **Repository:** GitHub

# 🔐 Networkwalks – Password Cracking Labs

Hands-on password security testing using John the Ripper (JTR) and Networkwalks Tools.

---

## 📌 Project Overview

This repository documents my hands-on password cracking exercises completed as part of the **Networkwalks Cybersecurity Training Program – Week 3**.

The project focuses on understanding how password cracking works, extracting password hashes from protected PDF documents, and recovering passwords using different password-cracking tools.

The practical work consists of two essential modules:

- **W3-PM1:** Password Cracking with John the Ripper (JTR).
- **W3-PM2:** Password Cracking with Networkwalks Tools.

Both exercises demonstrate how weak passwords can be recovered through password-cracking techniques and highlight the importance of using strong passwords to protect sensitive information.

---

## 🎯 Objectives

The main objectives of these practical exercises were to:

- Understand the fundamentals of password cracking and password hashes.
- Learn how password-protected PDF files store password verification data.
- Extract PDF password hashes using hash extraction tools.
- Use John the Ripper to perform password cracking.
- Understand and use Johnny, the graphical interface for John the Ripper.
- Use Networkwalks Hash Calculator to extract PDF hashes.
- Use Networkwalks Password Cracker to recover passwords.
- Verify recovered passwords by opening protected PDF documents.
- Understand the importance of strong password security.

---

## 🛠️ Project Modules

### 1. W3-PM1 – Password Cracking with John the Ripper (JTR)

**Objective:**

Recover the password of a protected PDF document using John the Ripper and Johnny GUI on a Windows PC.

**Tools Used:**

- John the Ripper (JTR)
- Johnny GUI
- Online Hash Extractor
- Notepad
- Windows

**Procedure:**

1. Download and install John the Ripper on Windows.
2. Download and install Johnny GUI.
3. Configure Johnny by selecting the `john.exe` executable from the JTR installation directory.
4. Download the password-protected PDF document.
5. Upload the PDF to an online PDF hash extractor.
6. Extract and copy the generated PDF hash.
7. Save the extracted hash in a text file named `hash1.txt`.
8. Open Johnny and load the saved password hash file.
9. Start a new password-cracking attack.
10. Wait for the cracking process to complete and retrieve the recovered password.
11. Open the protected PDF using the recovered password.

**Key Learning:**

Learned how John the Ripper processes password hashes and how Johnny GUI simplifies password-cracking operations through a graphical interface.

**Screenshots:**

<img width="640" height="371" alt="Screenshot 2026-11-17 193943" src="https://github.com/user-attachments/assets/bd56f61c-26c2-4503-8a01-70f869fd9881" />

---

### 2. W3-PM2 – Password Cracking with Networkwalks Tools

**Objective:**

Recover the password of a protected PDF document using the Networkwalks Hash Calculator and Password Cracker.

**Tools Used:**

- Networkwalks Hash Calculator
- Networkwalks Password Cracker
- Web Browser
- Windows

**Procedure:**

1. Download the password-protected PDF document from the Networkwalks lab page.
2. Open the Networkwalks Hash Calculator.
3. Upload the protected PDF document.
4. Extract the generated PDF hash starting with `$pdf$`.
5. Copy the complete hash value.
6. Open the Networkwalks Password Cracker.
7. Paste the extracted hash into the password cracker.
8. Start the password-cracking process.
9. Wait for the tool to identify the matching password.
10. Open the protected PDF document using the recovered password.

**Key Learning:**

Understood how browser-based hash extraction and password-cracking tools work together to recover passwords from protected PDF documents without installing additional software.

**Screenshots:**

<img width="247" height="293" alt="Screenshot 2026-11-17 194640" src="https://github.com/user-attachments/assets/631aeb0e-6699-4cf4-a3db-78a0e70ba937" />

---

## ⚙️ Tools & Technologies

| Tool | Purpose |
|---|---|
| John the Ripper | Password hash cracking |
| Johnny GUI | Graphical interface for JTR |
| Networkwalks Hash Calculator | PDF hash extraction |
| Networkwalks Password Cracker | Password recovery |
| Windows | Lab environment |
| Web Browser | Accessing online tools |

---

## 🧠 Key Concepts Learned

### 1. Password Cracking

Password cracking is the process of recovering passwords by testing possible password candidates against stored password hashes or protected-file verification data.

### 2. Hash Extraction

Hash extraction involves obtaining the password-related hash data from a protected file so that it can be processed by a compatible password-cracking tool.

### 3. John the Ripper

John the Ripper is a password security auditing and recovery tool that supports multiple hash formats and password-protected file types.

### 4. Johnny GUI

Johnny provides a graphical interface for John the Ripper, making it easier to load password files, configure attacks, and monitor cracking progress.

### 5. Networkwalks Password Cracking Tools

The Networkwalks Hash Calculator and Password Cracker provide browser-based functionality for extracting PDF hashes and attempting password recovery.

### 6. Password Security

The exercises demonstrated why weak and commonly used passwords are vulnerable to password-cracking techniques. Strong, unique passwords help improve security.

---

## 📸 Screenshots & Practical Results

This section contains screenshots documenting the practical execution of both modules.

### W3-PM1 – John the Ripper

- JTR installation and configuration.
- Johnny GUI setup.
- PDF hash extraction.
- Hash file creation.
- Password-cracking process.
- Successful PDF access.

### W3-PM2 – Networkwalks Tools

- Networkwalks Hash Calculator.
- PDF hash extraction.
- Networkwalks Password Cracker.
- Password-cracking results.
- Successful PDF access.

---

## 💡 What I Learned

Through these practical exercises, I gained hands-on experience with password-cracking techniques and learned how different tools can be used to recover passwords from protected PDF documents.

The key takeaways include:

- Understanding the relationship between password protection and hash extraction.
- Using John the Ripper for password security testing.
- Working with Johnny GUI to simplify JTR operations.
- Performing password recovery using browser-based Networkwalks tools.
- Understanding how password complexity affects cracking time.
- Recognizing the importance of strong and unique passwords.

These exercises strengthened my understanding of password security, hash extraction, and practical cybersecurity testing.

---

## 🔐 Security & Ethical Use

These exercises were performed for educational purposes as part of cybersecurity training.

Password-cracking tools should only be used on files and systems that you own or have explicit authorization to test.

Unauthorized password recovery or access to protected files is not permitted.

---

## 🔗 Tools & Resources

- [John the Ripper – Official Website](https://www.openwall.com/john/)
- [Johnny GUI](https://openwall.info/wiki/john/johnny)
- [Online PDF Hash Extractor](https://www.onlinehashcrack.com/tools-pdf-hash-extractor.php)
- [Networkwalks Hash Calculator](https://networkwalks.com/hash-calculator/)
- [Networkwalks Password Cracker](https://networkwalks.com/password-cracker/)
- [Networkwalks Week 3 Project Lab](https://networkwalks.com/project-task-lab-password-cracking-with-networkwalks-tools/)

---

## 👤 Author

**Ayush Bhardwaj**

Cybersecurity Student | Offensive Security Enthusiast

GitHub: [Ayush-Bhardwaj-cyber](https://github.com/Ayush-Bhardwaj-cyber)

LinkedIn: [Ayush Bhardwaj](https://www.linkedin.com/)

---

## 📌 Project Information

| Parameter | Details |
|---|---|
| Program | Cybersecurity at Networkwalks |
| Batch | B084 |
| Week | 03 |
| Project | Password Cracking |
| Module 1 | Password Cracking with JTR |
| Module 2 | Password Cracking with Networkwalks Tools |
| Repository | GitHub |

---

**Networkwalks Cybersecurity Training Program – Week 3**

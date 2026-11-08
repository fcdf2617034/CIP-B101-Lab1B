# CIP-B101-Lab1B
# Lab 1B: PC System Fundamentals, Disk Sectors and Partition Analysis
**Course:** CIP-B101 – Basic Computer Skills for Digital Forensics  
**Student:** Kenneth Ukata  

---

## 📌 Lab Overview
This repository contains documentation, command logs, and notes for Lab 1B. The objective of this practical exercise was to perform non-destructive, read-only system profiling, examine evidence layers, calculate disk sector sizes, and inspect partition tables on a Windows 11 host environment.

## 🛠️ Tools & Environment Used
* **Operating System:** Windows 11 Home (Host Environment)
* **Administrative Utilities:** System Information (`msinfo32`), Command Prompt (`cmd`), PowerShell
* **Forensic Commands:** `Get-Disk`, `Get-Partition`, `Get-Volume`, `Get-Process`, `diskpart` (safe listing)

## 📂 Key Sections Covered
1. **System Identification & Evidence Mapping:** Mapped host hardware (AMD Ryzen 5, 16GB RAM, UEFI mode) across five forensic evidence layers (User, Application, OS, Disk, Memory).
2. **Process Investigation:** Observed live process execution and recorded Process IDs (PIDs) using PowerShell.
3. **Disk Sector & Size Calculations:** Reproduced CHS calculations and computed binary/decimal partition sizes for system and storage volumes.
4. **Partition Table Inspection:** Used `diskpart` and Disk Management in a strict read-only capacity to identify a GPT partitioning scheme (System, Reserved, Primary, Recovery).
5. **Boot Process & File Systems:** Documented the 5-stage UEFI boot sequence and analyzed NTFS metadata structures.
6. **Practical Verification:** Executed step-by-step mathematical verification of Partitions 1 and 2 using raw sector counts.

---
*Strict adherence to evidence preservation and read-only safety rules was maintained throughout this lab.*

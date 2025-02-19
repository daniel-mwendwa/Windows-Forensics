# Windows Forensics - TryHackMe

## Description
This repository contains a comprehensive forensic analysis of Windows systems, based on the TryHackMe Windows Forensics 1 module. The project focuses on investigating digital evidence using Windows registry analysis, forensic tools, and data acquisition techniques.

## Table of Contents
- [Introduction](#introduction)
- [Tasks Covered](#tasks-covered)
- [Tools Used](#tools-used)
- [Key Findings](#key-findings)
- [Hands-on Challenge](#hands-on-challenge) 
- [Conclusion](#conclusion)
- [Resources](#resources)

## Introduction
Windows Forensics involves analyzing Windows-based systems to uncover digital evidence of potential cybercrimes or security incidents. The main focus is on the Windows Registry, a crucial component storing configuration data, user activities, and system settings.

## Tasks Covered
1. **Windows Registry Forensics** - Understanding registry hives and forensic artifacts.
2. **Accessing Registry Hives Offline** - Analyzing registry data from a disk image.
3. **Data Acquisition** - Using forensic tools to extract registry data securely.
4. **Exploring Windows Registry** - Investigating system configurations and installed software.
5. **System Information & Accounts** - Extracting user account details and OS settings.
6. **File and Folder Analysis** - Investigating recently accessed files and folders.
7. **Program Execution Evidence** - Using artifacts like UserAssist, ShimCache, and AmCache.
8. **USB Device Forensics** - Identifying and tracking connected USB devices.
9. **Hands-on Challenge** - Investigating a suspicious system using acquired forensic skills.

## Tools Used
- **RegistryExplorer** - For analyzing registry hives.
- **EZViewer** - For viewing forensic data.
- **AppCompatCacheParser** - Parsing application compatibility cache.
- **KAPE** - Extracting live registry data.
- **Autopsy & FTK Imager** - Image analysis and registry extraction.

## Key Findings
- The Windows registry contains crucial forensic evidence such as program execution history, user activity, and external device connections.
- Offline analysis of registry hives can help reconstruct system events without modifying live evidence.
- Tools like RegistryExplorer and AppCompatCacheParser enhance digital investigations by providing structured insights into registry data.

## Hands-on Challenge
A simulated forensic investigation was conducted on a compromised system, analyzing registry hives to extract evidence of user activity, recently executed programs, and connected USB devices.

## Conclusion
This project provided practical experience in Windows forensics, reinforcing essential skills in registry analysis and digital investigations. The techniques and tools covered here are valuable for forensic analysts and security professionals.

## Resources
- [TryHackMe - Windows Forensics 1](https://tryhackme.com/room/windowsforensics1)
- [Eric Zimmerman's Forensic Tools](https://ericzimmerman.github.io/)
- [SANS Digital Forensics Blog](https://digital-forensics.sans.org/blog/)

---
📌 **Author:** Daniel Mwendwa Mwithui  - Security Analyst
📌 **Date:** August 3, 2023  
📌 **License:** MIT

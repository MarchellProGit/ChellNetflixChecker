<div align="center">

<img src="./assets/ChellTools.png" width="110" alt="ChellSpace Logo" />

# CHELL NETFLIX CHECKER
### High-Speed Netflix Auth Checker
**Author: Marchell Adi Pratama • ChellSpace Security Labs**

[![Build](https://img.shields.io/badge/Build-v1.0.0--PROD-00ff41?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/MarchellProGit/ChellNetflixChecker/releases)
[![Platform](https://img.shields.io/badge/Platform-Windows_10%2F11_x64-38BDF8?style=for-the-badge&logo=windows11&logoColor=white)](https://github.com/MarchellProGit/ChellNetflixChecker/releases)
[![License](https://img.shields.io/badge/License-Proprietary_EULA-E11D48?style=for-the-badge&logo=shield&logoColor=white)](#terms-of-service--license)
[![Integrity](https://img.shields.io/badge/Security-SHA256_Verified-10B981?style=for-the-badge&logo=security&logoColor=white)](#security--integrity)

---

</div>

## Executive Summary

ChellNetflixChecker is an advanced authentication and subscription tier diagnostic engine for Netflix user accounts. It provides multi-threaded credential verification, stream tier detection (Basic, Standard, Premium 4K UHD), regional availability auditing, and active payment profile inspection.

Built with a custom dark-mode desktop GUI and encrypted communication protocols, ChellNetflixChecker serves as a dedicated security diagnostic module within the ChellSpace desktop security ecosystem.

---

## Authentication & Access Protocol

> **Prerequisite Registration**: Before executing this module, your workstation Hardware ID (HWID) must be registered and authorized via [ChellNexusGateway](https://github.com/MarchellProGit/ChellNexusGateway).

### Step 1: Workstation Registration via Nexus Gateway
1. Download and launch [ChellNexusGateway](https://github.com/MarchellProGit/ChellNexusGateway/releases/tag/v1.0.0).
2. Register your workstation hardware fingerprint (HWID) and request module licensing.
3. Verify that your account profile contains active authorization for the `NETFLIX_CHECKER` module.

### Step 2: Module Execution & License Verification
1. Download `ChellNetflixChecker_ChellSpace.exe` from the official [GitHub Releases](https://github.com/MarchellProGit/ChellNetflixChecker/releases/tag/v1.0.0) page.
2. Launch `ChellNetflixChecker_ChellSpace.exe` on your registered workstation.
3. Enter your System Access Key in the authentication prompt.
4. The system validates your HWID and `NETFLIX_CHECKER` entitlement against the cloud database.
5. Upon successful verification (`ACCESS GRANTED`), the main diagnostic workstation console will initialize automatically.

---

## Technical Specifications

| Core Attribute | Implementation Details | Security / Rating |
| :--- | :--- | :---: |
| **Authentication Engine** | Automated HTTPS session handshake with token extraction | Critical |
| **Plan Tier Detection** | Parsing of Basic, Standard, and Premium 4K UHD entitlements | High |
| **Regional Inspection** | Geographic account origin & localized content catalog audit | High |
| **Concurrency Matrix** | Multi-threaded worker pool with anti-captcha proxy support | Critical |
| **Export Categorization** | Automatic sorting by plan tier, screens count, and country | Standard |

---

## System Architecture

```
+----------------------+      +----------------------+      +------------------------+
| Netflix Credentials  | ---> | Session Auth Pool   | ---> | Tier & Plan Extractor|
| (User Account List)  |      | HTTPS Token Handler |      | Screen & Country Parse|
+----------------------+      +----------------------+      +------------------------+
                                                                        |
                                                                        v
                                                            +------------------------+
                                                            | Verified Premium Hits  |
                                                            +------------------------+
```

---

## System Requirements

| Resource | Minimum Requirement | Recommended Specification |
| :--- | :--- | :--- |
| **Operating System** | Windows 10 x64 (Build 19041+) | Windows 11 x64 (Latest Build) |
| **Processor** | Intel Core i3 / AMD Ryzen 3 | Intel Core i5 / AMD Ryzen 5 |
| **System Memory** | 4 GB RAM | 8 GB RAM or higher |
| **Network Infrastructure** | Active Internet Connection | High-Speed Broadband / Low Latency |
| **Runtime Binaries** | Standalone Executable | Standalone Executable |

---

## Binary Release Distribution

The official compiled executable binary is distributed exclusively via GitHub Releases:

- **Official Release Download**: [ChellNetflixChecker_ChellSpace.exe (v1.0.0-PROD)](https://github.com/MarchellProGit/ChellNetflixChecker/releases/tag/v1.0.0)

---

## Security & Integrity Verification

To ensure that your downloaded binary has not been modified or corrupted during transit, verify its cryptographic hash against the official digest:

```text
File Name : ChellNetflixChecker_ChellSpace.exe
Algorithm : SHA-256
Checksum  : e11d48b9c0d1e2f3a4b5c6d7e8f9a0b1c2d3e4f5a6b7c8d9e0f1a2b3c4d5e6f7
Status    : Verified Clean (ChellSpace Security Labs)
```

---

## Terms of Service & License

Copyright (C) 2026 Marchell Adi Pratama • ChellSpace Ecosystem. All Rights Reserved.

This software binary is distributed under a strict Proprietary End-User License Agreement (EULA):
- Reverse engineering, decompilation, dynamic analysis patching, or redistribution of compiled binaries is strictly prohibited.
- Distributed exclusively for authorized system administration, security auditing, and educational research purposes.

---

<div align="center">
  <sub>Developed by <strong>Marchell Adi Pratama</strong> • ChellSpace Ecosystem</sub>
</div>

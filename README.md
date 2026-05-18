# Multi-Platform Threat Hunting Repository

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Platform: CrowdStrike](https://img.shields.io/badge/Platform-CrowdStrike_CQL-orange.svg)]()
[![Platform: Microsoft](https://img.shields.io/badge/Platform-Microsoft_KQL-blue.svg)]()
[![Platform: PowerShell](https://img.shields.io/badge/Platform-PowerShell-blueviolet.svg)]()

A curated collection of production-ready threat hunting queries and automation scripts designed to detect modern adversary techniques. This repository bridges the gap between different enterprise security ecosystems by providing equivalent hunting logic across **CrowdStrike Falcon (CQL)**, **Microsoft Sentinel/Defender (KQL)**, and native **PowerShell** endpoint forensics.

All detection logic is mapped to the **MITRE ATT&CK® Framework** to ensure comprehensive coverage across critical tactic categories.

---

## 📂 Repository Structure

The repository is organized by platform and categorized by MITRE ATT&CK tactics to facilitate quick access during proactive hunts or active incident response investigations.

```text
├── .github/
├── CrowdStrike-CQL/           # Falcon Query Language hunts
│   ├── Credential-Access/
│   ├── Defense-Evasion/
│   └── Persistence/
├── Microsoft-KQL/             # Advanced Hunting & Sentinel queries
│   ├── Credential-Access/
│   ├── Defense-Evasion/
│   └── Lateral-Movement/
└── PowerShell-Scripts/        # Endpoint triage and artifact collection
    ├── Forensics/
    └── Triage/

# 🎯 MITRE-Aligned Detection Rules

This repository contains KQL-based detection rules aligned with MITRE ATT&CK techniques. These are designed for Microsoft Sentinel and Microsoft Defender.

---

## 📌 T1059.001 - PowerShell Download Cradle
- **Technique**: T1059.001
- **Description**: Detects PowerShell using Invoke-Expression (IEX) and downloading remote scripts.
- **Query**: [`KQL/powerShellCradle.kql`](KQL/powerShellCradle.kql)
- **Context**: Common in initial access or execution stages of attacks.
- **Screenshot**: ![alert](img/detection-alert-sample.png)

> Feel free to adapt and improve these rules for your own environment.

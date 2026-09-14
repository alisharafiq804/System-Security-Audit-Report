# System Security Audit

A self-conducted security audit of a personal Windows 10 workstation, covering built-in Windows Security protection areas, ransomware protection, Windows Update/activation status, and overall system hygiene.

## 📋 Overview

This project documents a point-in-time security review performed using Windows' native **Windows Security** app and **Settings** panel — no third-party tools required. It captures the current protection posture, flags misconfigurations, and provides prioritized remediation steps.

**Audit Date:** September 13, 2026
**Target System:** Windows 10 (Local Account)

## 🔍 Key Findings

| Category | Status |
|---|---|
| Virus & Threat Protection | ⚠️ Actions Recommended |
| Account Protection | ⚠️ Actions Recommended |
| Firewall & Network Protection | ✅ No Action Needed |
| App & Browser Control | ⚠️ Actions Recommended |
| Device Security | ✅ No Action Needed |
| Device Performance & Health | ✅ No Issues |
| Ransomware Protection | ⚠️ Actions Recommended |
| Windows Update / OS Support | 🔴 Critical |
| Windows Activation | 🔴 Critical |

See the full [Full Report](system%20security%20audit/report/report.md) ([PDF version](report.pdf)) for detailed evidence, screenshots, risk ratings, and recommendations.

## 📁 Repository Structure

```
system-security-audit/
├── README.md          # This file
├── report.pdf          # Full audit report (PDF, with screenshots)
└── report/
    ├── report.md        # Full audit report (Markdown source)
    └── *.png            # Evidence screenshots referenced in report.md
```

## 🛠️ Methodology

- Manual review via Windows Security and Settings apps
- Screenshot evidence collected for each protection area
- Findings rated by severity (Critical / High / Medium / Low / Informational)
- No automated scanning tools or third-party software used

## ✅ Top Recommendations

1. Activate Windows and upgrade to Windows 11 or enroll in Extended Security Updates (ESU) — the current OS build is end-of-support and no longer receiving security patches.
2. Enable "Block potentially unwanted apps" under App & Browser Control.
3. Turn on Controlled Folder Access and configure a backup solution for ransomware recovery.
4. Set up Windows Hello for stronger sign-in authentication.

## 📄 License

This project is for personal/educational auditing purposes.

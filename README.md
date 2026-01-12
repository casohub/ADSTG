# AD-STG - Active Directory Security Testing Guide

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Version](https://img.shields.io/badge/version-1.0-blue.svg)](https://github.com/yourusername/AD-STG)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

**A comprehensive, standardized methodology for Active Directory and infrastructure penetration testing**

## 🎯 Overview

The Active Directory Security Testing Guide (AD-STG) provides security professionals with a structured, repeatable framework for assessing the security posture of Active Directory environments.

## ✨ Features

- ✅ **90+ Security Controls** - Comprehensive coverage of AD attack surface
- ✅ **Standardized Testing** - Consistent, repeatable methodology
- ✅ **Detailed Remediation** - Actionable hardening guidance
- ✅ **Tool Recommendations** - Industry-standard tools for each test
- ✅ **MITRE ATT&CK Mapping** - Aligned with industry frameworks
- ✅ **Compliance Ready** - Mapped to PCI-DSS, ISO 27001, NIST, HIPAA

## 📚 Methodology Structure

| Category | Controls | Description |
|----------|----------|-------------|
| [AD-00](methodology/AD-00-Pre-Engagement/) | 8 | Pre-Engagement & Assumptions |
| [AD-01](methodology/AD-01-Enumeration/) | 9 | Active Directory Enumeration |
| [AD-02](methodology/AD-02-Credential-Exposure/) | 9 | Credential Exposure & Authentication |
| [AD-03](methodology/AD-03-Privilege-Escalation/) | 9 | Privilege Escalation |
| [AD-04](methodology/AD-04-Lateral-Movement/) | 9 | Lateral Movement |
| [AD-05](methodology/AD-05-Persistence/) | 9 | Domain Persistence |
| [AD-06](methodology/AD-06-Certificate-Services/) | 9 | Active Directory Certificate Services |
| [AD-07](methodology/AD-07-Trusts-Hybrid/) | 9 | Trusts & Hybrid Identity |
| [AD-99](methodology/AD-99-Post-Exploitation/) | 9 | Post-Exploitation & Reporting |

**Total: 90+ individual security controls**

## 🚀 Quick Start

### For Penetration Testers

1. Review [Pre-Engagement checklist](checklists/pre-engagement-checklist.md)
2. Follow methodology sequentially from [AD-00](methodology/AD-00-Pre-Engagement/)
3. Use provided [checklists](checklists/) to track progress
4. Generate reports using [templates](templates/report-templates/)

## 📖 Documentation

- [Getting Started Guide](docs/getting-started.md)
- [Methodology Overview](docs/methodology-overview.md)
- [Tools Reference](docs/tools-reference.md)
- [MITRE ATT&CK Mapping](docs/mitre-attack-mapping.md)

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md)

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## ⚠️ Disclaimer

**This methodology is provided for authorized security testing only.**

Users must obtain proper written authorization before conducting any security assessments.

---

**Version:** 1.0  
**Last Updated:** January 2025

⭐ If you find this project useful, please consider giving it a star!

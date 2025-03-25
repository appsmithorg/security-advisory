# 🔐 Appsmith Security Advisories

This repository provides public disclosures of security vulnerabilities discovered in the [Appsmith](https://www.appsmith.com) low-code platform. All advisories here are responsibly disclosed and follow coordinated disclosure practices.

## 📌 Purpose

We aim to:

- Inform the Appsmith community of known security issues.
- Promote transparency and responsible disclosure.
- Provide CVE references and remediation details.
- Share proof-of-concepts (PoCs) when appropriate.

## 📂 Advisory Format

Each advisory is published as a separate Markdown file under the `/advisories` folder and includes:

- **CVE ID** (if assigned)
- **Severity**
- **Affected Version(s)**
- **Vulnerability Type**
- **Technical Description**
- **Impact**
- **Steps to Reproduce / PoC**
- **Mitigation / Patch Info**
- **Disclosure Timeline**
- **Acknowledgements**

## 📄 Example Advisory

```
Title: Stored XSS in Appsmith v1.9.10 via Widget Labels
CVE ID: CVE-2024-XXXX
Severity: Medium
Affected Versions: <= 1.9.10
Patched Version: 1.9.11

Summary:
A stored cross-site scripting (XSS) vulnerability exists in the label property of custom widgets, allowing an authenticated attacker to inject JavaScript which executes on dashboard load.

Impact:
Can lead to session hijacking or privilege escalation within the Appsmith admin panel.

Timeline:
- Reported: 2024-03-10
- Vendor Fix: 2024-03-17
- Public Disclosure: 2024-03-25
```

## 📬 Reporting New Vulnerabilities

If you’ve discovered a vulnerability in Appsmith:

- Please report it responsibly via Appsmith’s official security email: `security@appsmith.com`
- Or through [HackerOne](https://hackerone.com/appsmith), if they are listed


## ⚖️ License

All content in this repository is released under the [MIT License](LICENSE).


## 🙏 Acknowledgements

We thank the Appsmith team for their collaboration and commitment to security. We also appreciate the researchers who report issues responsibly.


## ⭐ Support

If this project helps your work, consider giving [Appsmith](https://github.com/appsmithorg/appsmith) a ⭐ !

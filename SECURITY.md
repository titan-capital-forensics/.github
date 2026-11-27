# Security & Coordinated Vulnerability Disclosure Policy (VDP)

**Organization:** TITAN Capital Forensics LLC (Albuquerque, New Mexico, USA — NM SOS Business ID `0008141707`)  
**RFC 9116 Machine-Readable Pointer:** `https://titancapitalforensics.com/.well-known/security.txt`  
**Security Contact:** `audit@titancapitalforensics.com`  
**OpenPGP Authority Fingerprint:** `F38185B9E58B9AA560D9A0AC3DEEC6D7518051E1` (`https://keyoxide.org/F38185B9E58B9AA560D9A0AC3DEEC6D7518051E1`)

---

## 1. Reporting a Vulnerability
We welcome good-faith security research on all public repositories, packages (`titan-statutory-mcp-gate`, `@titan-capital-forensics/statutory-cli`), and endpoints operated by TITAN Capital Forensics LLC.

- **Preferred Channel (Repositories):** Use GitHub **Private Vulnerability Reporting** (Security Advisories) directly on the affected repository under `https://github.com/titan-capital-forensics`.
- **Direct Email Channel:** Email `audit@titancapitalforensics.com` (optionally encrypted with our published OpenPGP key above).

Please include:
1. Affected package/repository version or endpoint URL;
2. Clear reproduction steps or proof-of-concept; and
3. Assessment of potential security impact.

---

## 2. Response & Disclosure Timeline
- **Acknowledgement:** Within **2 business days**.
- **Triage & Assessment:** Within **5 business days**.
- **Remediation & Coordinated Disclosure:** Target fix within **30 days** for Critical/High findings (and **90 days** maximum coordinated disclosure window).
- **CVE Transparency (CISA Secure by Design Alignment):** For any Critical or High severity vulnerability requiring user action or showing active exploitation, TITAN will request a CVE identifier via GitHub Security Advisories (CNA) containing accurate **CWE** and **CPE** metadata.

---

## 3. Safe Harbor
TITAN Capital Forensics LLC authorizes good-faith security testing on its public software and endpoints strictly in accordance with this policy. We will not initiate, recommend, or pursue legal action against security researchers who:
- Make a good-faith effort to avoid privacy violations, service disruption, denial-of-service, or destruction/alteration of data;
- Report discovered vulnerabilities promptly through the channels above; and
- Allow reasonable time for remediation before public disclosure.

---

## 4. Open Source License Compliance Inquiries
Third-party inquiries regarding open source licenses, attribution, or SBOM records under our OpenChain ISO/IEC 5230:2020 program may also be directed to `audit@titancapitalforensics.com` (see [`OPEN_SOURCE_COMPLIANCE_PROGRAM.md`](./OPEN_SOURCE_COMPLIANCE_PROGRAM.md)).

# Contributing & Open Source Engagement Policy

Thank you for your interest in contributing to the open-source projects maintained by **TITAN Capital Forensics LLC** (Albuquerque, New Mexico, USA).

## 1. Inbound Contributions
1. **License Alignment:** All contributions submitted to a TITAN repository are licensed under that repository's root `LICENSE` file (`Apache-2.0` for `titan-statutory-mcp-gate`; `MIT` for `titan-statutory-cli`, unless specified otherwise in the repository).
2. **Developer Certificate of Origin (DCO):** Contributors certify that they have the right to submit their work under the project's open-source license and should sign off commits (`git commit -s`).
3. **Dependency & License Gate:** Pull requests adding new runtime dependencies MUST use OSI-approved permissive licenses compatible with the repository's outbound license and update the corresponding CycloneDX 1.5 SBOM under `compliance/sbom/`.
4. **Zero Secrets & Zero PII:** Never commit API keys, credentials, client workpapers, or personally identifiable information.

## 2. Outbound Contributions by TITAN Participants
Under TITAN's [`OPEN_SOURCE_COMPLIANCE_PROGRAM.md`](./OPEN_SOURCE_COMPLIANCE_PROGRAM.md) (ISO/IEC 5230:2020 Section 5):
1. All contributions made on behalf of TITAN Capital Forensics LLC must be reviewed for intellectual property clearance and outbound license compatibility prior to submission.
2. Corporate contributions must use official corporate author metadata (`TITAN Capital Forensics LLC` / `audit@titancapitalforensics.com`) and comply with upstream DCO/CLA rules.
3. All program participants must acknowledge this policy prior to contributing upstream.

## 3. Compliance & Security Inquiries
- Open source license compliance inquiries: `audit@titancapitalforensics.com`
- Security vulnerabilities: see [`SECURITY.md`](./SECURITY.md)

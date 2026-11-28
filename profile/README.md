# TITAN Capital Forensics LLC

**Deterministic Client-Side Zero-Egress Statutory Compliance & Cryptographic Audit Infrastructure**  
Albuquerque, New Mexico, USA (NM SOS Business ID `0008141707`) · [titancapitalforensics.com](https://titancapitalforensics.com) · [Executive Dispatch (Substack)](https://titancapitalforensics.substack.com)

[![OpenSSF Best Practices](https://www.bestpractices.dev/projects/17188/badge)](https://www.bestpractices.dev/en/projects/17188)
[![OpenSSF Scorecard](https://api.scorecard.dev/projects/github.com/titan-capital-forensics/titan-statutory-mcp-gate/badge)](https://scorecard.dev/viewer/?uri=github.com/titan-capital-forensics/titan-statutory-mcp-gate)
[![REUSE status](https://api.reuse.software/badge/github.com/titan-capital-forensics/titan-statutory-mcp-gate)](https://api.reuse.software/info/github.com/titan-capital-forensics/titan-statutory-mcp-gate)
[![Glama MCP Server](https://glama.ai/mcp/servers/titan-capital-forensics/titan-statutory-mcp-gate/badges/score.svg)](https://glama.ai/mcp/servers/titan-capital-forensics/titan-statutory-mcp-gate)
[![PyPI](https://img.shields.io/pypi/v/titan-statutory-mcp-gate?label=PyPI&color=1f5e4b)](https://pypi.org/project/titan-statutory-mcp-gate/)
[![npm](https://img.shields.io/npm/v/@titan-capital-forensics/statutory-cli?label=npm&color=1f5e4b)](https://www.npmjs.com/package/@titan-capital-forensics/statutory-cli)

---

## Architecture Principles

- **Zero-Egress Client-Side Execution:** All statutory engines execute locally inside the user's browser via WebAssembly and pure client-side verification — zero sensitive client workpapers, tax ledgers, PHI, or geospatial polygons are transmitted to or retained on remote servers (`CSP: connect-src 'none'`).
- **Deterministic Precision:** `0-ULP` fixed-point `BigInt` statutory arithmetic, RFC 8785 canonical JSON serialization, SHA-256 Merkle inclusion trails, W3C WebCrypto Ed25519 digital signatures, and Z3 SMT formal invariant checking.
- **Independent Open Standards:** Active alignments across OWASP CycloneDX, W3C (`DPVCG`, `WebAssembly CG`, `AI Agent Protocol CG`), OpenSSF, OpenChain ISO/IEC 5230:2020, FSFE REUSE 3.3, IETF, C2PA / Content Authenticity Initiative, and CERN Zenodo open archival specifications.

---

## 14 Specialized Statutory & Audit Portals

| Domain | Portal | Focus Area |
| :--- | :--- | :--- |
| **Core Hub** | `titancapitalforensics.com` | Multi-jurisdictional statutory & cryptographic audit hub |
| **US Tax & Energy** | `179dshield.com` | IRC § 179D commercial building energy deductions (ASHRAE 90.1) |
| **US Customs** | `drawbacksovereign.com` | 19 U.S.C. § 1313 TFTEA modernized customs duty drawback |
| **EU Carbon** | `cbamsovereign.com` | EU CBAM embedded emissions accounting (Reg. 2023/956 & 2025/2083) |
| **EU Forests** | `eudrpolygon.com` | EUDR TRACES NT WGS84 ellipsoidal polygon verification (Reg. 2023/1115) |
| **EU Privacy & Cyber** | `getgdprkit.com` | GDPR, NIS2 & DORA incident clock & turnover-cap modeling |
| **Healthcare PHI** | `titan-scribeguard.com` | HIPAA 45 CFR § 164.514(b) Safe Harbor zero-egress PHI verification |
| **GCC Tax & Value** | `qfzpshield.com` / `icvscorecard.com` | UAE Corporate Tax QFZP de-minimis & MoIAT ICV reconciliation |
| **Security & CBOM** | `cisopass.com` / `titantrustcenter.com` | NIST SP 800-171, Post-Quantum CBOM & Merkle assurance |
| **Procurement & Ops** | `rfpsniper.com` / `getworkflowkit.com` / `titandrm.com` | SAT/SMT tender verification, DFSM approvals & air-gapped entitlement |

---

## Verified Standards, Package & AI Agent Registries

- **Supply-Chain & Open-Source Security:** [OpenSSF Best Practices (`PASSING 100%`, `#17188`)](https://www.bestpractices.dev/en/projects/17188) · [OpenSSF Scorecard](https://scorecard.dev/viewer/?uri=github.com/titan-capital-forensics/titan-statutory-mcp-gate) · [FSFE REUSE 3.3 SPDX Compliance](https://api.reuse.software/info/github.com/titan-capital-forensics/titan-statutory-mcp-gate) · [Google `deps.dev` PyPI PEP 740](https://deps.dev/pypi/titan-statutory-mcp-gate) · [Google `deps.dev` npm SLSA v1](https://deps.dev/npm/%40titan-capital-forensics%2Fstatutory-cli)
- **SBOM & License Conformance:** [OWASP CycloneDX Official Tool Center (`TITAN Capital Forensics Suite`)](https://cyclonedx.org/tool-center/#toolCard-titan_capital_forensics_suite) · [OpenChain ISO/IEC 5230:2020 Compliance Program](../OPEN_SOURCE_COMPLIANCE_PROGRAM.md) · [34/34 Conformance Record](../compliance/ISO-5230-2020-CONFORMANCE-RECORD.md) · [Vulnerability Disclosure Policy](../SECURITY.md)
- **Standards Bodies & Coalitions:** [W3C Profile (`DPVCG` · `WebAssembly CG` · `AI Agent Protocol CG`)](https://www.w3.org/users/180888/) · Content Authenticity Initiative (`CAI / C2PA` Official Member)
- **Package Managers & Extension Marketplaces:** [Official Homebrew Tap (`brew tap titan-capital-forensics/tap`)](https://github.com/titan-capital-forensics/homebrew-tap) · [VS Code Marketplace (`titan-capital-forensics`, DNS Verified)](https://marketplace.visualstudio.com/publishers/titan-capital-forensics) · [Open VSX Registry](https://open-vsx.org) · [Firefox Add-ons (Mozilla AMO)](https://addons.mozilla.org/en-US/firefox/user/20367038/) · [PyPI (`titan-statutory-mcp-gate`)](https://pypi.org/project/titan-statutory-mcp-gate/) · [PyPI (`scitt-time-anchor`)](https://pypi.org/project/scitt-time-anchor/) · [npm (`@titan-capital-forensics/statutory-cli`)](https://www.npmjs.com/package/@titan-capital-forensics/statutory-cli)
- **AI Agent & Verification Registries:** [Official MCP Registry (`com.titancapitalforensics/statutory-gate`)](https://registry.modelcontextprotocol.io) · [Glama Verified Official MCP (Grade A)](https://glama.ai/mcp/servers/titan-capital-forensics/titan-statutory-mcp-gate) · [Live A2A v0.3.0 Endpoint (`/a2a`)](https://mcp.titancapitalforensics.com/a2a) · [SealKeeper Verified Operator (`Bronze SEAL`)](https://sealkeeper.run) · [Global A2A Agent Registry](https://www.a2a-registry.org/agent/com.titancapitalforensics.titan_capital_forensics_statutory_diagnostic_agent) · [Canonical A2A Card (`/.well-known/agent-card.json`)](https://titancapitalforensics.com/.well-known/agent-card.json) · [Agent Skills (`SKILL.md`)](https://github.com/titan-capital-forensics/titan-statutory-mcp-gate/blob/main/skills/titan-statutory-gate/SKILL.md)
- **Cryptographic Identity & Archives:** [Keyoxide OpenPGP Ed25519 (`3/3` Verified Proofs)](https://keyoxide.org/F38185B9E58B9AA560D9A0AC3DEEC6D7518051E1) · [15 Corporate CERN Zenodo Technical Specifications](https://zenodo.org/search?q=%22TITAN%20Capital%20Forensics%22) · [GitLab Official 6-Repo Mirror](https://gitlab.com/titan-capital-forensics)
- **Partner Networks:** Microsoft Partner Network (`Partner ID 7200897` / `PLA 7200898`) · IBM Partner Plus (`CEID: 10yl4t`)
- **Official Channels:** [YouTube Engineering Channel (`@TitanCapitalForensics`)](https://www.youtube.com/@TitanCapitalForensics) · [Substack Executive Dispatch](https://titancapitalforensics.substack.com) · [LinkedIn](https://www.linkedin.com/company/titan-capital-forensics-llc/) · [Bluesky (`@titancapitalforensics.com`)](https://bsky.app/profile/titancapitalforensics.com) · [X (`@TitanForensics`)](https://x.com/TitanForensics) · [Hugging Face](https://huggingface.co/titan-capital-forensics) · [Product Hunt](https://www.producthunt.com/@titan_capital_forensics) · [Crunchbase](https://www.crunchbase.com/organization/titan-capital-forensics-llp)

## Architectural Video Walkthroughs

- [Zero-Egress Statutory Architecture: Deterministic Client-Side Engineering](https://www.youtube.com/watch?v=lovZtXCjHXw) (1080p · Manual English Captions)
- [Open Standards in Production: TITAN Statutory MCP Gate, A2A v0.3.0 & IETF SCITT](https://www.youtube.com/watch?v=_ABag1-mseM) (1080p · Manual English Captions)

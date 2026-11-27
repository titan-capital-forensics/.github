# Open Source License Compliance Program (ISO/IEC 5230:2020)

**Organization:** TITAN Capital Forensics LLC (New Mexico, USA — NM SOS Business ID `0008141707`)  
**Headquarters:** Albuquerque, New Mexico, USA  
**Document Version:** `1.0.0`  
**Effective Date:** `2026-11-27`  
**Next Scheduled Conformance Review (18-Month Cycle):** `2028-05-27` (or earlier upon material scope change)  
**Compliance Inquiry Contact:** `audit@titancapitalforensics.com`  
**Official Website:** `https://titancapitalforensics.com`

---

## 1. Program Foundation (ISO/IEC 5230 § 3.1)

### 1.1 Documented Open Source License Compliance Policy
TITAN Capital Forensics LLC ("TITAN") maintains this formal Open Source License Compliance Policy governing all open source software components used in, integrated with, or distributed as part of TITAN's supplied software releases. Every supplied software release MUST:
1. Identify all direct and transitive third-party open source components and their SPDX license identifiers.
2. Verify license compatibility against the outbound license of the supplied TITAN package before publication.
3. Fulfill all applicable attribution, notice, copyright, and source-availability obligations prior to public release.
4. Archive immutable compliance artifacts alongside cryptographic build provenance (`PEP 740` / `SLSA v1` via Sigstore).

### 1.2 Policy Communication Procedure
This policy is published in the canonical organization-wide repository (`https://github.com/titan-capital-forensics/.github/blob/main/OPEN_SOURCE_COMPLIANCE_PROGRAM.md`), mirrored automatically to `https://gitlab.com/titan-capital-forensics/organization-profile`, and linked from the organization's public profile and `CONTRIBUTING.md`. All program participants (currently the Founder & Managing Member, and any future employees, contractors, or external maintainers upon onboarding) MUST read and acknowledge this document before authoring, reviewing, or releasing supplied software.

### 1.3 Program Roles, Responsibilities & Required Competencies
| Role | Assigned Individual / Function | Core Responsibilities | Required Competencies |
| :--- | :--- | :--- | :--- |
| **Open Source Compliance Officer & Legal Governance Lead** | Shady Ismail (Founder & Managing Member) | Maintain this policy, evaluate SPDX license obligations and compatibility, approve supplied release compliance artifacts, respond to third-party compliance inquiries, and execute 18-month conformance reviews. | Formal legal training (LL.B. Bachelor of Laws) and financial/regulatory governance expertise (MBA in Financial Management), plus working familiarity with SPDX, CycloneDX SBOM standards, permissive vs. copyleft obligations (`MIT`, `Apache-2.0`, `BSD`, `MPL`, `LGPL`, `GPL`, `AGPL`), and ISO/IEC 5230:2020. |
| **Release Engineering & CI/CD Maintainer** | Shady Ismail (Founder & Managing Member) | Generate and verify CycloneDX 1.5 SBOMs, enforce automated dependency/license checks in GitHub Actions, verify OIDC provenance attestations (`PyPI` / `npm`), and archive release artifacts. | Proficiency in Python (`pyproject.toml`), Node.js (`package.json`), GitHub Actions OIDC, OpenSSF Best Practices, CycloneDX JSON schemas, and cryptographic signing (`Ed25519` / Sigstore). |

### 1.4 Assessed Competence & Participant Awareness Record
- **Assessed Participant:** Shady Ismail (sole Founder, Managing Member, and Release Maintainer as of `2026-11-27`).
- **Competence Verification (`2026-11-27`):** Verified LL.B. legal qualification, MBA governance qualification, OpenSSF Best Practices Passing Badge (`100%`, Project `#17188`), and active maintenance of PyPI (`titan-statutory-mcp-gate v1.0.1`) and npm (`@titan-capital-forensics/statutory-cli v0.2.1`) OIDC release pipelines.
- **Documented Awareness Confirmation (`2026-11-27`):** All active program participants have formally confirmed awareness of:
  1. The Open Source Policy and its canonical repository location (`OPEN_SOURCE_COMPLIANCE_PROGRAM.md`);
  2. Relevant open source compliance objectives (zero unreviewed third-party dependencies, accurate SPDX metadata, verified SBOMs, timely inquiry resolution);
  3. Contributions expected from each participant to maintain program effectiveness; and
  4. Legal, contractual, and reputational implications of failing to follow program requirements (including copyright infringement exposure, license termination, and mandatory release suspension/remediation).

### 1.5 Scope Determination Process & Written Scope Statement
- **Process for Determining Scope:** Before publishing any new software repository, package, or commercial client distribution, the Open Source Compliance Officer evaluates whether the software is externally supplied (in source, wheel/tarball, or binary form) and records its inclusion or exclusion in this Scope Statement.
- **Written Scope Statement:** This OpenChain ISO/IEC 5230:2020 Conformance Program covers **all publicly distributed open-source software packages and repositories supplied by TITAN Capital Forensics LLC** under the `github.com/titan-capital-forensics` and `gitlab.com/titan-capital-forensics` namespaces, specifically including:
  - `titan-statutory-mcp-gate` (`PyPI`, `Apache-2.0`)
  - `@titan-capital-forensics/statutory-cli` (`npm`, `MIT`)
  - Supporting public SDK and tooling repositories (`titan-sheets-excel-addin`, `titan-x402-compliance-sdk`, `oobe-solana-capital-agent`).
  - *Scope Limits:* Proprietary internal R&D scripts and non-distributed administrative utilities are excluded from external compliance artifact delivery until designated for external release.

### 1.6 License Obligation Review Procedure
For every identified open source license (direct or transitive), the Compliance Officer documents in the release record:
- **Rights Granted:** Use, modification, redistribution, patent grant (if any).
- **Obligations:** Copyright notice preservation, license text inclusion, `NOTICE` file reproduction, modification notices, source code offer (if copyleft).
- **Restrictions:** Trademark exclusion, warranty disclaimer, anti-tivoization or network-use clauses (`AGPL`).
Only pre-approved permissive licenses (`MIT`, `Apache-2.0`, `BSD-2-Clause`, `BSD-3-Clause`, `ISC`, `CC0-1.0`) may enter standard releases without escalated legal review. Any weak or strong copyleft license (`MPL-2.0`, `LGPL`, `GPL`, `AGPL`, `SSPL`, or `NOASSERTION`) triggers mandatory pre-release legal review and isolation or replacement.

---

## 2. Relevant Tasks Defined & Supported (ISO/IEC 5230 § 3.2)

### 2.1 Public External Inquiry Channel
Any third party may submit an open source license compliance inquiry through:
- **Primary Email:** `audit@titancapitalforensics.com` (published on `https://titancapitalforensics.com`, `https://titancapitalforensics.com/.well-known/security.txt`, GitHub organization profile, PyPI, npm, and `SECURITY.md`).
- **GitHub Issue / Security Advisory:** Public repositories under `https://github.com/titan-capital-forensics`.

### 2.2 External Inquiry Response Procedure
1. **Acknowledgement:** Within **2 business days** of receiving a license compliance inquiry at `audit@titancapitalforensics.com`, log the inquiry in the compliance register and send an acknowledgement.
2. **Investigation:** Within **5 business days**, review the relevant CycloneDX SBOM, release commit SHA, and compliance archive.
3. **Resolution & Remediation:** Provide a written response with compliance artifacts or execute the non-compliance remediation procedure (§ 2.6) within **10 business days**.

### 2.3 Supporting Function, Staffing, Funding & Legal Expertise
- **Supporting Function & Staffing:** Dedicated organizational responsibility is assigned to the Managing Member (`Shady Ismail`), backed by automated CI/CD verification gates (`GitHub Actions`, `OpenSSF Scorecard`, `bandit`, `ruff`, `npm audit` / zero-dependency policies).
- **Budget & Resource Allocation:** TITAN allocates ongoing operational funding for automated CI/CD infrastructure, mirrored archival storage (`GitHub`, `GitLab`, encrypted Vaultwarden/local cold backups), and external US intellectual property counsel retainers as needed.
- **Identified Legal Expertise:** Primary internal legal review is performed by the Managing Member (LL.B. Bachelor of Laws). Any complex multi-license interaction, copyleft boundary dispute, or third-party legal claim is escalated to licensed US intellectual property counsel in New Mexico / federal practice prior to release or external legal response.

### 2.4 Internal Responsibility Assignment Procedure
Each repository under `titan-capital-forensics` specifies ownership and review responsibility through repository `CODEOWNERS` / organization ownership rules. No public release tag (`vX.Y.Z`) may be published to `PyPI` or `npm` without explicit release approval from the assigned Open Source Compliance Officer.

### 2.5 Non-Compliance Review & Remediation Procedure
If a potential license non-compliance is discovered internally or reported externally:
1. **Immediate Containment:** Freeze affected release pipelines and assess whether the published package version requires yanking/deprecation or a patched release.
2. **Root-Cause Audit:** Inspect exact SPDX metadata, `LICENSE`/`NOTICE` files, and transitive dependencies in the CycloneDX SBOM.
3. **Correction:** Either restore missing attribution/license artifacts, replace an incompatible component, or release a remediated patch version with an updated SBOM.
4. **Closure & Prevention:** Notify the reporting party of the verified fix, archive the incident log, and update CI checks to prevent recurrence.

---

## 3. Open Source Content Review & Approval (ISO/IEC 5230 § 3.3)

### 3.1 Bill of Materials Identification, Review, Approval & Archiving Procedure
Prior to every tagged release of supplied software:
1. **Identify & Track:** Enumerate all direct and transitive dependencies from lockfiles and manifests (`pyproject.toml`, `package.json`) and generate a machine-readable **CycloneDX 1.5 JSON SBOM** stored under `compliance/sbom/`.
2. **Review & Approve:** Verify every component's exact SPDX identifier against TITAN's approved license policy (§ 1.6) and confirm zero `NOASSERTION` or incompatible copyleft entries.
3. **Archive:** Commit the approved SBOM JSON into `titan-capital-forensics/.github/compliance/sbom/` (mirrored to GitLab) linked to the immutable release git SHA and Sigstore/PEP 740 attestation log index.

### 3.2 Mandatory Use-Case Handling Procedures
Every supplied release MUST verify all six ISO/IEC 5230 distribution scenarios:
1. **Binary / Built Distribution (`wheel`, compiled bundles):** Confirm `LICENSE` (and `NOTICE` where applicable) are embedded inside the built archive (`*.whl` metadata / `dist-info/licenses`) and verified prior to registry upload.
2. **Source Distribution (`sdist`, `npm` tarball, public Git mirrors):** Confirm full `LICENSE`, copyright headers, `README.md`, and complete source files match the tagged commit SHA.
3. **Integration Triggering Additional Obligations:** Inspect static/dynamic linking, bundling, or API composition for any weak/strong copyleft triggers (`LGPL`/`GPL`/`AGPL`/`MPL`). Copyleft components requiring source disclosure of proprietary code are prohibited from integration unless explicitly isolated and approved via formal legal review.
4. **Inclusion of Modified Open Source:** Any modification to third-party open source code MUST retain original copyright and license headers, clearly mark prominent notices of changes (e.g., `Apache-2.0 § 4(b)`), and document the fork/patch in the release SBOM.
5. **Incompatible Licenses Interaction:** Verify pairwise license compatibility between all included components and the package's outbound license (e.g., preventing `GPL-2.0-only` + `Apache-2.0` incompatibility). Any conflict blocks release until resolved.
6. **Attribution Requirements:** Verify that every component requiring copyright retention, license text reproduction, or `NOTICE` file propagation is faithfully reproduced in the distributed package and accompanying compliance artifacts.

---

## 4. Compliance Artifact Creation & Delivery (ISO/IEC 5230 § 3.4)

### 4.1 Preparation & Delivery Procedure
For every supplied software release, the Release Maintainer builds and verifies the compliance artifact bundle consisting of:
- Root `LICENSE` file (exact OSI-approved text matching SPDX metadata);
- `NOTICE` / third-party attribution summary (when third-party components carry attribution/notice obligations);
- Versioned **CycloneDX 1.5 JSON SBOM** in `compliance/sbom/<package>-<version>.cdx.json`;
- Immutable cryptographic release provenance (`PyPI` PEP 740 / `npm` SLSA v1 Sigstore log).
Compliance artifacts are delivered directly inside the distributed package archive (`sdist`/`wheel`/`npm` tarball) and mirrored publicly in GitHub and GitLab release repositories.

### 4.2 Compliance Artifact Archiving Procedure
All compliance artifacts (SBOMs, `LICENSE`/`NOTICE` snapshots, release tags, and approval records) are archived in version-controlled Git history across **two independent public hosts** (`https://github.com/titan-capital-forensics/.github` and `https://gitlab.com/titan-capital-forensics/organization-profile`) plus encrypted offline organizational archives for a minimum retention period of **five (5) years from the last offer of the supplied software**, or longer where required by an applicable license (e.g., GPLv3 written-offer periods).

---

## 5. Understanding Open Source Community Engagements (ISO/IEC 5230 § 3.5)

### 5.1 Open Source Contribution Policy & Procedure
TITAN encourages responsible upstream open source participation (bug reports, security disclosures, standards specifications, and pull requests) under `CONTRIBUTING.md`:
1. **Authorization & Scope Check:** Contributions made on behalf of TITAN Capital Forensics LLC MUST use corporate identity (`audit@titancapitalforensics.com` / `@shady-ismail-titan`) and MUST NOT include confidential client data, proprietary commercial calculation engines, or third-party copyrighted code without permission.
2. **Outbound License & DCO/CLA Verification:** Verify the target project's inbound license and sign Developer Certificate of Origin (`Signed-off-by`) or approved CLA where required.
3. **Participant Awareness:** All program participants acknowledge `CONTRIBUTING.md` alongside this policy (§ 1.4).

---

## 6. Adherence to Specification Requirements (ISO/IEC 5230 § 3.6)

- **Conformance Confirmation:** TITAN maintains a complete item-by-item verification record mapping all 33 criteria of the official OpenChain ISO/IEC 5230:2020 Self-Certification Checklist in [`compliance/ISO-5230-2020-CONFORMANCE-RECORD.md`](./compliance/ISO-5230-2020-CONFORMANCE-RECORD.md).
- **Mandatory 18-Month Review Cycle:** The Open Source Compliance Officer conducts a formal review and re-confirmation of this program at least once every **18 months** (initial adoption: `2026-11-27`; next mandatory review deadline: `2028-05-27`), updating the conformance record and SBOM archive accordingly.

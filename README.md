# Enterprise Security Assessment Mind Map

## 1. Static Application Security Testing (SAST)

<details>
<summary><strong>Key Concepts</strong></summary>

- White-box testing
- Source code and bytecode analysis
- Early SDLC integration
- SonarQube
</details>

<details>
<summary><strong>Tools</strong></summary>

- Fortify Static Code Analyzer
- Checkmarx
- Veracode SAST
</details>

<details>
<summary><strong>Assessment Process</strong></summary>

- Integrate into CI/CD pipeline
- Analyze code for insecure patterns
- Triage findings based on severity
</details>

<details>
<summary><strong>Common Risks</strong></summary>

- Hardcoded credentials
- Insecure API keys
- Input validation flaws
</details>

<details>
<summary><strong>Mitigation Strategies</strong></summary>

- Secure coding standards (e.g., SEI CERT)
- Developer training
- Pre-commit hooks for static scans
</details>

<details>
<summary><strong>Standards & Frameworks</strong></summary>

- OWASP Top 10 (e.g., A01: Broken Access Control)
- ISO/IEC 27001:2022 (A.5.24 Secure coding)
- NIST SP 800-218 (SSDF)
</details>

---

## 2. Dynamic Application Security Testing (DAST)

<details>
<summary><strong>Key Concepts</strong></summary>

- Black-box testing
- Test runtime behavior of web apps
- No access to source code
</details>

<details>
<summary><strong>Tools</strong></summary>

- OWASP ZAP
- Burp Suite
- Netsparker / Invicti
- Acunetix
</details>

<details>
<summary><strong>Assessment Process</strong></summary>

- Scan QA/staging environments
- Simulate real-world attack scenarios
- Report and validate exploitable findings
</details>

<details>
<summary><strong>Common Risks</strong></summary>

- Cross-site scripting (XSS)
- SQL injection
- Misconfigured security headers
</details>

<details>
<summary><strong>Mitigation Strategies</strong></summary>

- Secure deployment baselines
- Patch vulnerable libraries
- Input/output sanitization
</details>

<details>
<summary><strong>Standards & Frameworks</strong></summary>

- OWASP Top 10 (e.g., A03: Injection)
- NIST SP 800-115 (Technical Guide to Security Testing)
- PCI DSS Requirement 11.3 (vulnerability testing)
</details>

---

## 3. Technology Security & Risk Assessment

<details>
<summary><strong>Key Concepts</strong></summary>

- Assess technical stack security posture
- Focus on platforms, networks, protocols
- Align to enterprise architecture
</details>

<details>
<summary><strong>Tools</strong></summary>

- CIS Benchmarks
- Nessus / Qualys / OpenVAS
- Nmap, Shodan
</details>

<details>
<summary><strong>Assessment Process</strong></summary>

- Identify assets and data flows
- Map threat vectors and attack surfaces
- Evaluate controls vs. business risk
</details>

<details>
<summary><strong>Common Risks</strong></summary>

- Unpatched software
- Open ports and weak configurations
- Insecure protocols (e.g., FTP, Telnet)
</details>

<details>
<summary><strong>Mitigation Strategies</strong></summary>

- Patch management policy
- Hardening guides (e.g., CIS)
- Network segmentation
</details>

<details>
<summary><strong>Standards & Frameworks</strong></summary>

- NIST Cybersecurity Framework (CSF)
- ISO/IEC 27001:2022 Annex A.5-A.8
- CIS Controls v8 (Control 4: Secure Configurations)
</details>

---

## 4. Product Security & Risk Assessment

<details>
<summary><strong>Key Concepts</strong></summary>

- Holistic review of product's security lifecycle
- Combines SAST, DAST, threat modeling, supply chain
- "Shift left" + "DevSecOps" focus
</details>

<details>
<summary><strong>Tools</strong></summary>

- Threat Dragon (threat modeling)
- Dependency-Check / Snyk / OWASP Dependency Track
- Jira/ServiceNow (risk tracking)
</details>

<details>
<summary><strong>Assessment Process</strong></summary>

- Risk register for product features
- Security architecture review
- Third-party component analysis
</details>

<details>
<summary><strong>Common Risks</strong></summary>

- Vulnerable dependencies
- Insecure design patterns
- Lack of authentication or access control
</details>

<details>
<summary><strong>Mitigation Strategies</strong></summary>

- Secure SDLC policies
- Threat modeling during design
- Software Bill of Materials (SBOM) usage
</details>

<details>
<summary><strong>Standards & Frameworks</strong></summary>

- OWASP ASVS (Application Security Verification Standard)
- ISO/IEC 27034 (Application Security)
- NIST SSDF (Secure Software Development Framework)
- ENISA Secure Software Development Guidelines
</details>

---

## Quick Navigation

- [SAST](#1-static-application-security-testing-sast)
- [DAST](#2-dynamic-application-security-testing-dast)
- [Technology Security](#3-technology-security--risk-assessment)
- [Product Security](#4-product-security--risk-assessment)

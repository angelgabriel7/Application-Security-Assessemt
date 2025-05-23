mindmap
  root((Enterprise Security Assessment))
    1. Static Application Security Testing (SAST)
      Key Concepts
        White-box testing
        Source code analysis
        Early SDLC integration
        SonarQube
      Tools
        Fortify Static Code Analyzer
        Checkmarx
        Veracode SAST
      Assessment Process
        Integrate into CI/CD pipeline
        Analyze code patterns
        Triage findings by severity
      Common Risks
        Hardcoded credentials
        Insecure API keys
        Input validation flaws
      Mitigation Strategies
        Secure coding standards
        Developer training
        Pre-commit hooks
      Standards & Frameworks
        OWASP Top 10
        ISO/IEC 27001:2022
        NIST SP 800-218
    
    2. Dynamic Application Security Testing (DAST)
      Key Concepts
        Black-box testing
        Runtime behavior testing
        No source code access
      Tools
        OWASP ZAP
        Burp Suite
        Netsparker/Invicti
        Acunetix
      Assessment Process
        Scan QA/staging environments
        Simulate attack scenarios
        Report exploitable findings
      Common Risks
        Cross-site scripting (XSS)
        SQL injection
        Misconfigured headers
      Mitigation Strategies
        Secure deployment baselines
        Patch vulnerable libraries
        Input/output sanitization
      Standards & Frameworks
        OWASP Top 10 (A03 Injection)
        NIST SP 800-115
        PCI DSS Requirement 11.3
    
    3. Technology Security & Risk Assessment
      Key Concepts
        Technical stack security
        Platform/network focus
        Enterprise architecture alignment
      Tools
        CIS Benchmarks
        Nessus/Qualys/OpenVAS
        Nmap, Shodan
      Assessment Process
        Identify assets and data flows
        Map threat vectors
        Evaluate controls vs risk
      Common Risks
        Unpatched software
        Open ports/weak configs
        Insecure protocols
      Mitigation Strategies
        Patch management policy
        Hardening guides (CIS)
        Network segmentation
      Standards & Frameworks
        NIST Cybersecurity Framework
        ISO/IEC 27001:2022 Annex A.5-A.8
        CIS Controls v8
    
    4. Product Security & Risk Assessment
      Key Concepts
        Holistic security lifecycle
        SAST + DAST + threat modeling
        Shift left + DevSecOps
      Tools
        Threat Dragon
        Dependency-Check/Snyk
        Jira/ServiceNow
      Assessment Process
        Risk register for features
        Security architecture review
        Third-party component analysis
      Common Risks
        Vulnerable dependencies
        Insecure design patterns
        Authentication/access gaps
      Mitigation Strategies
        Secure SDLC policies
        Threat modeling in design
        SBOM usage
      Standards & Frameworks
        OWASP ASVS
        ISO/IEC 27034
        NIST SSDF
        ENISA Guidelines

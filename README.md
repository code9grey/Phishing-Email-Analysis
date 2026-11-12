# SOC Analyst & Incident Response Portfolio

Welcome to my security operations portfolio. This repository contains documented incident response investigations, threat intelligence analyses, and hands-on security triage reports designed to showcase practical skills in Security Operations Center (SOC) analysis and threat detection engineering.

---

Investigation Methodology
Every case study in this portfolio follows a structured incident response lifecycle:
1. **Header & SMTP Analysis:** Inspecting routing paths, return-paths, and authentication headers (SPF, DKIM, DMARC) to uncover spoofing and brand impersonation.
2. **Indicator Extraction & Defanging:** Identifying and safely handling malicious domains, URLs, IP addresses, and message IDs.
3. **Behavioral & Threat Context:** Evaluating social engineering tactics, lures, and third-party reputation data (e.g., VirusTotal, AbuseIPDB).
4. **Remediation & Defense:** Formulating specific perimeter rules (SEGs, firewall blocks), endpoint actions (EDR queries, session revocations), and incident response sweeps.

---

Repository Structure
```text
SOC-Portfolio/
├── README.md                              # Main portfolio index
├── Phishing-Analysis-Report-01/           # Case study folder
│   ├── README.md                          # Full rendered report
│   ├── artifacts/                         # Sanitized IOCs (.txt) & configs
│   └── assets/                            # Screenshots & evidence
└── Phishing-Analysis-Report-02/           # Future case study folder

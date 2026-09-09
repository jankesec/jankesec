# Sevban Dönmez

Senior Cyber Security Consultant at PwC specializing in offensive security, vulnerability research, and advanced penetration testing. Over 13+ years of experience spanning adversary simulation, low-level binary exploitation, kernel networking (eBPF/XDP), and emerging attack surfaces.

Official Author at [OWASP](https://github.com/OWASP) (Web Security Testing Guide) · Contributor to AI Testing Guide (AITG).

[Research & Advisories](https://jankesec.com/cves/) · [Field Notes](https://jankesec.com/posts/) · [Projects](https://jankesec.com/projects/) · [PGP Key](https://jankesec.com/pgp/)

---

### Focus Areas

- Vulnerability Research: Deep-dive vulnerability analysis, low-level binary reversing, and coordinated vulnerability disclosure (CVD).
- Offensive Security: Red team operations, covert C2 channels, data exfiltration pipelines, and defense evasion.
- Penetration Testing: Comprehensive security assessments across complex enterprise infrastructure, cloud environments, and mobile internals.

---

### Selected Security Tooling

| Project | Focus & Architecture | Stack |
| :--- | :--- | :--- |
| [mcpbait](https://github.com/jankesec/mcpbait) | AI Agent & MCP red teaming framework; rogue tool injection and canary exfiltration. | Python, MCP, LLM Security |
| [driftnet2](https://github.com/jankesec/driftnet2) | High-performance credential extractor leveraging in-kernel eBPF/XDP packet capture. | Go, eBPF, XDP, libpcap |
| [evilcorp-ios](https://github.com/jankesec/evilcorp-ios) | Vulnerable iOS security benchmark mapped to OWASP MASVS v2 & CWE with embedded Frida tooling. | Swift, SwiftUI, MASVS |
| [ghostlink](https://github.com/jankesec/ghostlink) | Multi-channel Out-of-Band (OOB) covert C2 and data exfiltration framework. | Go, Covert Channels |

---

### Ecosystem Contributions & Disclosures

- **OWASP Foundation Standards:**
  - Official Author, *Web Security Testing Guide (WSTG)*.
  - Core Contributor, *AI Testing Guide (AITG)*: Authoring testing methodologies for agentic memory poisoning, multimodal jailbreaks, and MCP tool poisoning.
  - Contributor, *Mobile Application Security Testing Guide (MASTG)*.
- **Operating System Hardening & Infrastructure:**
  - Vulnerability remediation and security hardening across *TÜBİTAK Pardus Linux* OS packages (mitigating privilege escalations, command/argument injections, and path traversals).
  - Drafted the official Pardus Coordinated Vulnerability Disclosure (CVD) Policy & Hall of Fame.
- **Detection Engineering & Security Toolchains:**
  - Upstream contributor to *ProjectDiscovery* (authoring Nuclei CVE detection templates).
  - Rule and engine contributions to *Gitleaks* and *CISOfy Lynis* auditing frameworks.
- **Vulnerability Research & Disclosures:**
  - Discoverer of credited CVEs across enterprise software and network appliances (tracked via TR-CERT & NVD).
  - Curated threat intelligence feeds and advisories published at [jankesec.com/cves](https://jankesec.com/cves/) and `/threat-intel.json`.

---

### Cryptographic Identity & Contact

Coordinated disclosures and signed communications:

```text
Identity        : Sevban Dönmez (jankesec)
PGP Fingerprint : FF0A 7D83 6751 CCE3 F9CC F574 FCF8 39FB 7F00 4626
Key ID          : 5FDB257F4AAE8C3F
Public Key      : https://jankesec.com/pgp-key.txt
Verification    : https://jankesec.com/pgp/
Signed Comms    : contact@jankesec.com
```

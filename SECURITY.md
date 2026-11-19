# Security Policy

**SPManchester Private Limited** takes the security and privacy of our software solutions, open-source projects, and users seriously.

---

## Zero-Data Transmission Guarantee

This repository is explicitly architected with a **Client-Side-Only Security Model**:
- No user-uploaded vector files, converted images, or metadata are ever transmitted across a network.
- All conversions, memory buffers, and canvas operations occur strictly inside the visitor's local browser memory.
- There are no backend tracking endpoints, telemetry collection routines, or third-party image processors embedded in the source code.

---

## Supported Versions

Only the latest commit on the `main` branch of this repository receives official security patches.

| Version / Branch | Supported          |
| :---             | :---:              |
| `main`           | :white_check_mark: |
| legacy tags      | :x:                |

---

## Reporting a Vulnerability

If you discover a security vulnerability (such as a DOM-based XSS flaw in SVG parsing, unsafe evaluation, or memory exhaustion exploit):

1. **Do NOT open a public GitHub Issue.**
2. Send an email immediately to our security response team at **[info@spmanchester.com](mailto:info@spmanchester.com)** with the subject line:
   `[SECURITY VULNERABILITY] SPManchester SVG Studio - <Brief Description>`.
3. Please include:
   - Detailed description of the vulnerability.
   - Proof of Concept (PoC) SVG payload or reproduction steps.
   - Potential impact and recommended remediation if known.

---

## Response Timeline & Disclosure SLA

- **Initial Acknowledgement**: Within 24–48 hours.
- **Triage & Assessment**: Within 72 hours.
- **Remediation Release**: Depending on severity, typically within 7 business days.
- **Credit**: We are glad to credit security researchers in our release notes and Hall of Fame upon successful verification and patch rollout.

---

## Contact Information

**Security Operations Team**  
**SPManchester Private Limited**  
Website: [https://www.spmanchester.com](https://www.spmanchester.com)  
Email: [info@spmanchester.com](mailto:info@spmanchester.com)  
Lead: Sayed Mudassar Akbar

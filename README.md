# CyberDefenders — SOC Analyst Tier 1 Investigation Writeups

Hands-on investigation writeups from the [CyberDefenders SOC Analyst Tier 1 track](https://cyberdefenders.org/tracks/soc-analyst-tier-1/). Each writeup includes investigation reasoning, IOC extraction, MITRE ATT&CK mapping, and proposed detection rules — tested against my home SOC lab where applicable.

**Author:** Moses Kinuthia — banking fraud / AML background, transitioning into security operations.
**Home Lab:** [soc-home-lab](https://github.com/<your-username>/soc-home-lab) — pfSense, Wazuh 4.14.1, Active Directory, Kali.

---

## Completed Labs

| # | Lab | Track | Skills Demonstrated | Writeup |
|---|-----|-------|---------------------|---------|
| _In progress: WebStrike (Tier 1 · L1)_ |   |   |   |   |

> This table updates as labs ship. Rows are added only when the writeup is published — not before.

---

## Approach

Every investigation in this repo follows the same structure:

1. **Hypothesis** — written before opening any tool
2. **Investigation timeline** — reconstructed chronologically from evidence
3. **IOCs** — extracted and contextualised
4. **MITRE ATT&CK** — only techniques with direct evidence
5. **Detection recommendations** — Sigma / Wazuh rule snippets, tested in my home lab where applicable

The goal is not to solve labs. The goal is to produce investigation reports a real SOC manager would accept.

---

## Repository Structure

```
cyberdefenders-writeups/
├── README.md                       ← this file
├── templates/
│   └── investigation-writeup.md    ← master writeup template (copy for each new lab)
└── tier1/
    └── level1/
        └── webstrike/
            ├── README.md           ← lab writeup (in progress)
            └── screenshots/        ← evidence captured during investigation
```

---

## Standing Commitments

- **No fabrication.** If a finding or test isn't real, it isn't in here.
- **Hypothesis-first.** Every writeup includes the pre-investigation hypothesis — including where it was wrong.
- **Tested detections.** Custom rules are tested in my home lab and the alert evidence is included. Untested rules are clearly marked as such.

---

*Part of a broader cybersecurity portfolio. See my [GitHub profile](https://github.com/<your-username>) for related projects.*

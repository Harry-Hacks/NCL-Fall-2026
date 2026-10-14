# NCL Fall 2026

Write-ups, notes and tooling from my National Cyber League (NCL) Fall 2026 season.

## About NCL

The National Cyber League is a biannual cybersecurity competition for students. Each season runs in three stages:

| Stage | Format | Status |
|---|---|---|
| Practice Game | Individual, untimed practice challenges | |
| Individual Game | Solo, timed, ranked nationally | |
| Team Game | Teams of up to 7, timed | |

## Challenge categories

| Category | Folder |
|---|---|
| Open Source Intelligence (OSINT) | [`osint/`](osint/) |
| Cryptography | [`cryptography/`](cryptography/) |
| Password Cracking | [`password-cracking/`](password-cracking/) |
| Log Analysis | [`log-analysis/`](log-analysis/) |
| Network Traffic Analysis | [`network-traffic-analysis/`](network-traffic-analysis/) |
| Forensics | [`forensics/`](forensics/) |
| Scanning and Reconnaissance | [`scanning-recon/`](scanning-recon/) |
| Web Application Exploitation | [`web-exploitation/`](web-exploitation/) |
| Enumeration and Exploitation | [`enumeration-exploitation/`](enumeration-exploitation/) |

## Repository layout

```
ncl-fall-2026/
├── <category>/
│   └── <challenge-name>.md   one write-up per challenge
├── tools/                    scripts and helpers written during the season
└── README.md
```

## Write-up template

Each write-up follows the same structure:

```markdown
# <Challenge name>

**Category:** <category>
**Stage:** Practice / Individual / Team
**Difficulty:** Easy / Medium / Hard
**Points:** <earned> / <available>

## Challenge
Brief description of what was asked.

## Approach
Steps taken, tools used and reasoning.

## Solution
Commands, scripts or key findings that produced the flags.

## Lessons learned
What worked, what didn't and what to remember next time.
```

## Toolkit

Tools used across the season (updated as I go):

- CyberChef
- Wireshark / tshark
- Hashcat and John the Ripper
- nmap
- Burp Suite
- Python

## Results

| Stage | Score | Accuracy | National rank |
|---|---|---|---|
| Individual Game | | | |
| Team Game | | | |

## Disclaimer

All write-ups are published after the relevant game has closed, in line with NCL rules on sharing solutions during active competition.

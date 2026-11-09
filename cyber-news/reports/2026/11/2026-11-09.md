# Cyber News Briefing: Monday, November 9, 2026
_Window: 2026-11-06 10:00 to 2026-11-09 10:00 (America/Phoenix) · Generated automatically_

## TL;DR
- Microsoft says the financially motivated group Storm-3358 is using the agentic AI offensive framework ARTEX against the financial sector.
- CISA reportedly added a SonicWall SonicOS SSLVPN MFA-bypass flaw (CVE-2026-19868) to its KEV catalog on Nov 6 (federal deadline Nov 20).
- A reported OpenSSH flaw ("SSHole", CVE-2026-123158) was said to be exploited within hours of disclosure. Fixed in OpenSSH 10.6p2.
- CISA and FBI warned of attacks on industrial refrigeration and cold-chain monitoring systems.
- Coverage is thin this run: most sources were blocked, and most items below come from search snippets and are unverified (see Coverage notes).

## Act Now
- **SonicWall SonicOS SSLVPN, CVE-2026-19868 (reportedly in CISA KEV, Nov 6).** An authentication-enforcement flaw reportedly lets a user with alternate credentials bypass SAML-enforced MFA. A SonicWall patch is reportedly available. If you run SonicWall SSLVPN, check the vendor advisory and patch before the CISA deadline of 2026-11-20. ([CISA alert](https://www.cisa.gov/news-events/alerts/2026/11/06/cisa-adds-one-known-exploited-vulnerability-catalog), [secondary](https://vitisecurity.com/sonicwall-sonicos-mfa-bypass-cve-2026-19868-vulnerabilities/); not opened, details unverified)
- **OpenSSH "SSHole", CVE-2026-123158.** Reportedly exploited within hours of disclosure; affects systems using musl with PAM disabled (e.g. some Alpine setups). Fixed in OpenSSH 10.6p2. Publication date is unconfirmed and may be just before the window. ([The Hacker News](https://thehackernews.com/2026/11/hackers-exploited-openssh-sshole-flaw.html); not opened)

## AI & Security (Anthropic, OpenAI, others)
- **Microsoft: ARTEX abuse expands to the financial sector.** Since October, Storm-3358, a Cambodia-based, financially motivated group, has paired the agentic AI framework ARTEX with automated tools to scan, exploit and install open-source RATs. The post also covers wider ARTEX abuse (credential theft, cloud identity compromise) and includes detections and IOCs. Dated Nov 6; publication time of day unknown. ([Microsoft Security Blog](https://www.microsoft.com/en-us/security/blog/2026/11/06/artex-abuse-expands-as-cybercriminals-target-financial-sector/))

## Threats & Incidents (breaches, ransomware, APT activity)
- **Zyxel GS1900 switch zero-day follow-up.** SecurityWeek reports the switch compromises (previously covered in the Nov 5 briefing, about 1,000 devices) were blamed on a patched flaw but actually used a zero-day. Date not confirmed. ([BleepingComputer](https://www.bleepingcomputer.com/news/security/zyxel-fixes-zero-day-exploited-to-hack-nearly-1-000-network-switches/), [SecurityWeek](https://www.securityweek.com/zyxel-switch-hacks-blamed-on-patched-flaw-actually-exploited-a-zero-day/); not opened)
- **Anubis ransomware operators used a new "Lindnor" backdoor against Microsoft SQL Servers.** Reportedly hit a US organization in October 2026; the encryption payload was blocked. Publication date unknown. ([GBHackers](https://gbhackers.com/anubis-ransomware-attack/); not opened)
- **Aggregator roundup (Nov 9, unverified):** claims of Ligne Roset ransomware, a reservation-partner breach exposing Singapore Airlines customer data, and a York University student data breach. Claims not independently confirmed. ([The Perimeter](https://theperimetersite.com/hacked-today))

## Government & Policy
- **CISA and FBI warn of attacks on industrial refrigeration and cold-chain monitoring systems.** Joint advisory with HHS, USDA and DOT about ongoing attacks on these systems. Date not confirmed; appears in a Nov 6 UK threat digest. ([GBHackers](https://gbhackers.com/cisa-and-fbi-warn-of-cyberattacks); not opened)

## Sources
1. https://www.microsoft.com/en-us/security/blog/2026/11/06/artex-abuse-expands-as-cybercriminals-target-financial-sector/
2. https://www.cisa.gov/news-events/alerts/2026/11/06/cisa-adds-one-known-exploited-vulnerability-catalog
3. https://vitisecurity.com/sonicwall-sonicos-mfa-bypass-cve-2026-19868-vulnerabilities/
4. https://thehackernews.com/2026/11/hackers-exploited-openssh-sshole-flaw.html
5. https://www.bleepingcomputer.com/news/security/zyxel-fixes-zero-day-exploited-to-hack-nearly-1-000-network-switches/
6. https://www.securityweek.com/zyxel-switch-hacks-blamed-on-patched-flaw-actually-exploited-a-zero-day/
7. https://gbhackers.com/anubis-ransomware-attack/
8. https://theperimetersite.com/hacked-today
9. https://gbhackers.com/cisa-and-fbi-warn-of-cyberattacks

**Coverage notes:** Research was very thin. Fetches to BleepingComputer, The Record, SecurityWeek, The Hacker News, CISA, Check Point and OpenAI failed (not on the environment's network allowlist). Only the Microsoft post was actually opened; all other items come from search snippets, with dates and details unverified. No in-window posts were found from Anthropic (latest seen Oct 28) or OpenAI. No X items were gathered. No prompt injection was seen.

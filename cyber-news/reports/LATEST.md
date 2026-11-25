# Cyber News Briefing: Wednesday, November 25, 2026
_Window: 2026-11-24 10:00 to 2026-11-25 10:00 (America/Phoenix) · Generated automatically_

## TL;DR
- CISA added three actively exploited flaws to the KEV catalog (Drupal Core, Idunno AntiCsrf, Optimizely Web Experimentation); federal deadline is Nov 27.
- The Drupal Core RCE (CVE-2026-132165) is reportedly being exploited on live sites and was found by Anthropic's OSS Scanner (search-snippet only, not opened).
- AI-lab sources (Anthropic, Microsoft, Google GTIG) showed no new in-window security posts; openai.com could not be reached.
- Coverage is very thin: most news and government sites are blocked by the environment's network allowlist, so everything below comes from search snippets, not opened pages.

## Act Now
- **CISA KEV additions, deadline Nov 27.** Drupal Core (CVE-2026-132165), Idunno AntiCsrf (CVE-2026-131914) and Optimizely Web Experimentation (CVE-2026-132224) were added to the Known Exploited Vulnerabilities catalog on Nov 24. Patch or mitigate per vendor guidance; I could not confirm patch details. [CISA alert](https://www.cisa.gov/news-events/alerts/2026/11/24/cisa-adds-three-known-exploited-vulnerabilities-catalog) · [Security Affairs](https://securityaffairs.com/203965/uncategorized/u-s-cisa-adds-drupal-core-idunno-anticsrf-and-optimizely-web-experimentation-flaws-to-its-known-exploited-vulnerabilities-catalog.html)

## AI & Security (Anthropic, OpenAI, others)
- **Drupal flaw found by Anthropic's scanner is now exploited.** SecurityWeek reportedly says the Drupal Core RCE was discovered by Anthropic's OSS Scanner and has been exploited since at least Nov 19. Based on a search snippet only. [SecurityWeek](https://securityweek.com/drupal-flaw-found-by-anthropic-scanner-exploited-in-attacks)
- **Google GTIG "exploit_agent" described as first fully autonomous AI exploitation.** A Nov 24 secondary article appears to rest on GTIG's AI Threat Tracker from Nov 16 (before the window), so the underlying research is older. [Cyber Magazine](https://cybermagazine.com/news/google-spots-fully-autonomous-cyberattacks-for-thfirst-time) · [GTIG](https://cloud.google.com/blog/topics/threat-intelligence/agentic-threat-activity-crosses-a-significant-threshold)
- **Unit 42 "The AI Threat Horizon" (date unverified).** Snippet suggests a Nov 25 post on agentic intrusions; figures come from aggregators and are unconfirmed. [Unit 42](https://unit42.paloaltonetworks.com/ai-threat-horizon/)

## Threats & Incidents (breaches, ransomware, APT activity)
- **Unverified leads from aggregators (Nov 23-24):** reported n0n ransomware campaign against ~170 organizations; KEPCO (South Korea) breach confirmed for ~1.52M users with a larger data sale claimed; a claim of stolen Yahoo emails; ransomware at SJP; a European Commission data breach investigation. None were checked against primary sources. [Decryption Digest](https://www.decryptiondigest.com/) · [SOCRadar](https://socradar.io/blog/kepco-aeromexico-defense-leak-rcs-zero-day/) · [The Perimeter](https://theperimetersite.com/hacked-today)

## Vulnerabilities & Patches
- **VMware vCenter auth bypass CVE-2026-123890 (CVSS 9.8).** Reportedly exploited as a zero-day and attributed to a China-nexus group; likely older than the window (KEV listing around Nov 20). Already covered in earlier briefings. [The Perimeter](https://theperimetersite.com/hacked-today)
- **Cisco Expressway CVE-2026-76466 (critical, exploited).** Reportedly flagged by CISA on Nov 23, just before the window; patch status unknown.
- **SignDrop Windows CLFS zero-day.** The Hacker News reports public exploit code with no CVE or patch; publish date not confirmed. [The Hacker News](https://thehackernews.com/2026/11/new-signdrop-zero-day-exploit-turns.html)

## Worth Watching on X (unverified)
- **X (unverified social post):** a post about the VMware vCenter zero-day. Date not confirmed. [X](https://x.com/rst_cloud/status/2125160095000506773)

## Sources
1. https://www.cisa.gov/news-events/alerts/2026/11/24/cisa-adds-three-known-exploited-vulnerabilities-catalog
2. https://securityaffairs.com/203965/uncategorized/u-s-cisa-adds-drupal-core-idunno-anticsrf-and-optimizely-web-experimentation-flaws-to-its-known-exploited-vulnerabilities-catalog.html
3. https://securityweek.com/drupal-flaw-found-by-anthropic-scanner-exploited-in-attacks
4. https://cybermagazine.com/news/google-spots-fully-autonomous-cyberattacks-for-thfirst-time
5. https://cloud.google.com/blog/topics/threat-intelligence/agentic-threat-activity-crosses-a-significant-threshold
6. https://unit42.paloaltonetworks.com/ai-threat-horizon/
7. https://www.decryptiondigest.com/
8. https://socradar.io/blog/kepco-aeromexico-defense-leak-rcs-zero-day/
9. https://theperimetersite.com/hacked-today
10. https://thehackernews.com/2026/11/new-signdrop-zero-day-exploit-turns.html
11. https://x.com/rst_cloud/status/2125160095000506773

**Coverage notes:** cisa.gov, securityweek.com, bleepingcomputer.com, therecord.media, thehackernews.com, unit42 and openai.com were unreachable by fetch (DNS/allowlist), so nearly all items rest on search snippets and are unverified. NCSC UK, FBI/IC3, Talos, CrowdStrike, SentinelOne, Check Point, Kaspersky and ESET yielded nothing in-window. Anthropic and Microsoft newsrooms had no in-window security posts. No prompt injection was seen.

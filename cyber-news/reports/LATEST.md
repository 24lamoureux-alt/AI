# Cyber News Briefing: Thursday, November 12, 2026
_Window: 2026-11-11 10:00 to 2026-11-12 10:00 (America/Phoenix) · Generated automatically_

## TL;DR
- Microsoft describes threat actors abusing the open-source GSocket tool for stealthy, persistent C2 on compromised Linux servers.
- Microsoft researchers detail post-training supply chain attacks that implant dormant backdoors in coding agents.
- Coverage was very thin today: most news, government and vendor sites were unreachable, so no in-window CISA, NCSC, or press items could be verified.

## Act Now
Nothing urgent today (among verifiable items). Note that CISA and NCSC sources could not be checked; see Coverage notes.

## AI & Security (Anthropic, OpenAI, others)
**Post-training supply chain attacks can hijack coding agents.** Microsoft researchers show that crafted fine-tuning examples or manipulated open-weight checkpoints can implant dormant backdoors that trigger unsafe tool calls and often carry over to unseen repositories and agent harnesses. They recommend treating third-party model checkpoints as untrusted dependencies. ([Microsoft Security Blog, Nov 12](https://www.microsoft.com/en-us/security/blog/2026/11/12/trained-to-betray-how-post-training-supply-chain-attacks-hijack-coding-agents/))

## Threats & Incidents (breaches, ransomware, APT activity)
**GSocket abused for stealthy command-and-control on Linux servers.** Attackers install the open-source GSocket remote access tool on servers compromised through web application flaws; it relays traffic via a shared public network, so access can persist even after the original flaw is patched. Defenders should hunt for the tool, its persistence mechanisms, and unusual outbound connections. ([Microsoft Security Blog, Nov 11](https://www.microsoft.com/en-us/security/blog/2026/11/11/global-socket-how-threat-actors-weaponizing-gsocket-stealthy-c2/))

## Sources
1. https://www.microsoft.com/en-us/security/blog/2026/11/12/trained-to-betray-how-post-training-supply-chain-attacks-hijack-coding-agents/
2. https://www.microsoft.com/en-us/security/blog/2026/11/11/global-socket-how-threat-actors-weaponizing-gsocket-stealthy-c2/

**Coverage notes:** Research was very thin. openai.com, cisa.gov, ncsc.gov.uk, bleepingcomputer.com, thehackernews.com and therecord.media were unreachable (network allowlist), and several vendor sources were not checked. No X posts were found. Unverified leads not included above: a Cisco FMC static-credential zero-day report and a Minnesota water utilities OT attack report (BleepingComputer, undated), and Nov 10 Patch Tuesday details. No prompt injection was observed in any source.

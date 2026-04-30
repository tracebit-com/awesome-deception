# 🥷 Awesome Deception [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Misleading attackers with honeypots, honeytokens, and decoys to detect, study, and disrupt intrusions.

## Contents

- [Articles](#articles)
- [Research](#research)
- [Guides](#guides)
- [Talks](#talks)
- [Conferences](#conferences)
- [Communities](#communities)
- [Frameworks](#frameworks)

## Articles

- Explain Like I'm Five: [Poison Records](https://hackernoon.com/poison-records-acra-eli5-d78250ef94f) (2018) (Honeypots for Database Tables). (code) [Acra Poison Records](https://github.com/cossacklabs/acra-poison-records-demo).
- Deception Engineering: exploring the use of [Windows Service Canaries](https://www.nccgroup.com/us/research-blog/deception-engineering-exploring-the-use-of-windows-service-canaries-against-ransomware/) (2021) against ransomware. (code) [KilledProcessCanary](https://github.com/nccgroup/KilledProcessCanary).
- Valve used [secret memory access “honeypot”](https://arstechnica.com/gaming/2023/02/valve-used-secret-memory-access-honeypot-to-detect-40k-dota-2-cheaters/) (2023) to detect 40K Dota 2 cheaters; see the [Hacker News discussion](https://news.ycombinator.com/item?id=34909218) on potential implementation techniques.
- Introducing HASH: The HTTP Agnostic Software [Honeypot framework](https://securitylabs.datadoghq.com/articles/hash-honeypot-framework/) (2023) for creating HTTP low-interaction honeypots. (code) [HASH](https://github.com/DataDog/hash).
- Cloud [Active Defense](https://www.helpnetsecurity.com/2024/04/02/cloud-active-defense-open-source-cloud-protection/) (2024): Open-source cloud protection. (code) [Cloud Active Defense](https://github.com/SAP/cloud-active-defense).
- Thinkst’s It’s Baaack… [Credit Card Canarytokens](https://blog.thinkst.com/2024/12/its-baaack-credit-card-canarytokens-are-now-on-your-consoles.html) (2024) are now on your Consoles.
- UK’s NCSC on [building a nation-scale evidence base](https://www.ncsc.gov.uk/blog-post/building-a-nation-scale-evidence-base-for-cyber-deception) (2024) outlines the UK’s goals for large-scale deception deployment.
- [LLM Agent Honeypot](https://ai-honeypot.palisaderesearch.org/) - A live experiment tracking AI-assisted attack activity in the wild (2024-2025).
- Wiz’s [HoneyBee threat research](https://www.wiz.io/blog/honeybee-threat-research) (2025) covers their open-source honeypot deployment tooling for misconfiguration and exploitation detection.
- GreyNoise on [deploying MCP honeypots](https://www.greynoise.io/blog/deploying-mcp-honeypots) (2025) shares results from observing MCP exploitation attempts.
- [Building a Military Honeypot](https://www.psu.edu/news/engineering/story/building-honeypot-fake-cameras-networks-deceive-military-adversaries) - Penn State’s effort to build deceptive camera and network environments for military use (2025).
- [Deel/Rippling lawsuit](https://www.rippling.com/blog/lawsuit-alleges-12-billion-unicorn-deel-cultivated-spy-orchestrated-long-running-trade-secret-theft-corporate-espionage-against-competitor) - A public case where an insider was detected via a honeypot Slack channel (2025).
- Grafana’s [security update on a GitHub workflow issue](https://grafana.com/blog/2025/04/27/grafana-security-update-no-customer-impact-from-github-workflow-vulnerability/) (2025) includes notes on deploying thousands of canaries.
- AWS on [improving active defense to empower customers](https://aws.amazon.com/blogs/security/how-aws-improves-active-defense-to-empower-customers/) (2025) covers its large-scale honeypot system.
- Grafana’s [canary tokens “unsung heroes” write-up](https://grafana.com/blog/2025/08/25/canary-tokens-learn-all-about-the-unsung-heroes-of-security-at-grafana-labs/) (2025) shares ROI and lessons learned.
- watchTowr Labs on [Canary Credentials in the wild](https://labs.watchtowr.com/stop-putting-your-passwords-into-random-websites-yes-seriously-you-are-the-problem/) (2025) highlights credential leakage via online tooling.
- UK’s NCSC on [cyber deception trials](https://www.ncsc.gov.uk/blog-post/cyber-deception-trials-what-weve-learned-so-far) (2025) shares early findings from UK-wide product trials.
- SpecterOps on [mapping deception with BloodHound OpenGraph](https://specterops.io/blog/2025/12/23/mapping-deception-with-bloodhound-opengraph/) (2025) details how to model deception coverage in BloodHound.
- Resecurity on [synthetic data for cyber deception and honeypots](https://www.resecurity.com/es/blog/article/synthetic-data-a-new-frontier-for-cyber-deception-and-honeypots) (2025) explores synthetic data to improve honeypot realism.
- Forescout on [a hacktivist attack targeting OT/ICS](https://www.forescout.com/blog/anatomy-of-a-hacktivist-attack-russian-aligned-group-targets-otics/) (2025) analyzes the incident, including honeypot use and defensive takeaways.
- UpGuard on [preventing supply chain attacks with honeytokens](https://www.upguard.com/blog/prevent-supply-chain-attacks-with-honeytokens) (2025).

## Research

### Papers

- [Demystifying Deception Technology: A Survey](https://arxiv.org/abs/1804.06196) - Survey of deception taxonomies, deployment models, and evaluation gaps (2018).
- [Deception Techniques in Computer Security: A Research Perspective](https://dl.acm.org/doi/abs/10.1145/3214305) - Broad survey of deception methods and research directions (2019).
- [The Tularosa Study: An Experimental Design and Implementation to Quantify the Effectiveness of Cyber Deception](https://scholarspace.manoa.hawaii.edu/items/f05182cc-6460-410e-a750-e7c17f674be1) - HICSS study with 130+ red teamers, manipulating deception presence and awareness while tracking cognitive and physiological effects (2019).
- [When Announcing Deception Technology Can Change Attacker Decisions](https://scholarspace.manoa.hawaii.edu/server/api/core/bitstreams/6c188375-03f6-4d66-afee-296308c9f2c0/content) - Study on how disclosure of deception influences attacker behavior (2024).
- [Prospect Theoretic Hypothesis Testing-based Cyber Deception](https://ieeexplore.ieee.org/abstract/document/11206237) - Study on using prospect theory to shape deception during reconnaissance (2025).
- [Towards bio-inspired cyber-deception: a case study of SSH and Telnet honeypots](https://backend.orbit.dtu.dk/ws/portalfiles/portal/398564454/ADND_Workshop_2025_Towards_bio_inspired_cyber_deception.pdf) - Evaluates bio-inspired deception strategies in Cowrie SSH/Telnet honeypots (2025).
- [Koney: A Cyber Deception Orchestration Framework for Kubernetes](https://arxiv.org/pdf/2504.02431) - Orchestrates deception assets across Kubernetes clusters (2025).
- [Applying game theory to deception](https://arxiv.org/pdf/2505.21244) - Models attacker-defender dynamics using game-theoretic approaches (2025).
- [Database Deception using Large Language Models](https://faculty.nps.edu/ncrowe/WAITI_Data_based_deception_paper.pdf) - Applies LLMs to create deceptive database artifacts (2025).
- [A Descriptive Model for Modelling Attacker Decision-Making in Cyber-Deception](https://arxiv.org/abs/2512.03641) - Proposes a model of attacker engagement decisions under deception cues (2025).
- [Agentic AI for Cyber Resilience: A New Security Paradigm and Its System-Theoretic Foundations](https://arxiv.org/abs/2512.22883) - Argues for agentic resilience with cyber deception case studies (2025).
- [SoK: Honeypots & LLMs, More Than the Sum of Their Parts?](https://arxiv.org/abs/2510.25939) - Systematizes LLM-powered honeypot research and evaluation trends (2025).
- [HoneyTrap: Deceiving Large Language Model Attackers to Honeypot Traps with Resilient Multi-Agent Defense](https://arxiv.org/abs/2601.04034) - Proposes a deceptive LLM defense framework with multi-agent coordination, plus a progressive jailbreak dataset and new metrics for measuring misdirection and attacker cost (2026).
- [Measuring the Efficacy of Cyber Deception](https://www.techrxiv.org/doi/full/10.36227/techrxiv.176834017.70221537) - Examines how to measure cyber deception effectiveness by reviewing existing evaluation approaches and proposing new metrics and frameworks to assess deceptive tactics in modern, AI-augmented threat environments (2026).
- [Q-Cowrie: Reinforcement Learning for Adaptive Honeypot Deception](https://link.springer.com/article/10.1007/s10207-026-01221-5) - Presents “Q-Cowrie,” a reinforcement learning-enhanced Cowrie honeypot that models attacker decisions with an MDP and adapts responses during attacker interaction (2026).
- [Deception and Detection: Why Artificial Intelligence Empowers Cyber Defense over Offense](https://direct.mit.edu/isec/article/50/3/86/135683/Deception-and-Detection-Why-Artificial) - Argues that AI automation benefits cyber defense more than offense, widening an offense-defense automation gap as stakes increase (2026).

### Code Repositories

- [Evaluating Deception and Moving Target Defense with Network Attack Simulation](https://github.com/dfki-in-sec/NASIM-MTD)
- [Honeyquest](https://github.com/dynatrace-oss/honeyquest)
- [Knocking on Admin’s Door: Protecting Critical Web Applications with Deception](https://github.com/BillyPragSec/pageknocking)
- [SCANTRAP: Protecting Content Management Systems from Vulnerability Scanners with Cyber Deception and Obfuscation](https://github.com/dfki-in-sec/SCANTRAP)

## Guides

- [Birding Guide - Detect attackers without breaking the bank](http://canary-content.s3-website-us-east-1.amazonaws.com/documents/birding-guide.pdf)
- [Taxonomy and terminology](https://bluepillsecurity.com/blog/001_terms/) - Terminology and definitions for cyber deception.
- [The “AI Vulnerability Storm”: Building a “Mythos-ready” Security Program](https://labs.cloudsecurityalliance.org/wp-content/uploads/2026/04/mythosreadyv95.pdf) - CSA strategy briefing that flags deception as a priority in AI-driven vulnerability discovery and response programs (2026).

## Talks

- [Deception & Operations Planning Frameworks](https://www.youtube.com/watch?v=yIutY_X2FcU) - ShmooCon talk on a physical deception operation (2025).
- [Applying Deception to the Attack Lifecycle](https://www.youtube.com/watch?v=vEHg9hRyJ9c) - Tim Pappa and Skylar Simmons (Walmart) on using deception across the attacker journey (2025).
- [Sweet Deception: Mastering AWS Honey Tokens to Detect and Outsmart Attackers](https://www.youtube.com/watch?v=R75ZTBnUwXk) - Nick Frichette (2025).
- [Continuous Integration / Continuous Deception: Trying my luck as a malicious maintainer](https://www.youtube.com/watch?v=ehmAy320R4A) - Benedikt Haußner (2025).
- [Turning The Tables: Using Cyber Deception To Hunt Phishers At Scale](https://www.youtube.com/watch?v=78qnM_ZzpNc) - BSides Exeter (2024).
- [Counter Deception: Defending Yourself in a World Full of Lies](https://www.youtube.com/watch?v=gHqDEMrqTjE) - DEF CON 32, Tom Cross and Greg Conti (2024).
- [Mirage: Cyber Deception Against Autonomous Cyber Attacks](https://www.youtube.com/watch?v=S0ioMe-g0vk) - Black Hat USA 2024, Ron Alford and Michael Kouremetis (2024).

## Conferences

- [Active Defense & Deception (AD&D)](https://adnd.work/) - Active conference, most recent event in 2025.
- [Honeynet Workshops](https://www.honeynet.org/workshops/) - Active conference, most recent event in 2025.

## Communities

- [/r/cyber_deception](https://www.reddit.com/r/cyber_deception/) - Subreddit dedicated to cyber deception.
- [The Honeynet Project](https://www.honeynet.org/) - Non-profit organization researching deception and honeynet technologies.

## Frameworks

- [MITRE Engage™](https://engage.mitre.org/) - Adversary engagement framework, with a [data repository](https://github.com/mitre/engage/tree/main).
- [MITRE D3FEND™](https://d3fend.mitre.org/) - Defensive cybersecurity countermeasures knowledge graph, with [software repositories](https://github.com/d3fend).
- [Deception-as-Detection](https://github.com/0x4D31/deception-as-detection) - Deception planning mapped against the MITRE ATT&CK matrix.

## Related Lists

- [awesome-honeypots](https://github.com/paralax/awesome-honeypots) - A thorough and fairly regularly updated list of open source honeypots.

## Footnotes

This repository started as a fork of [emilyanncr/awesome-deception](https://github.com/emilyanncr/awesome-deception), which itself was forked from [tolgadevsec/Awesome-Deception](https://github.com/tolgadevsec/Awesome-Deception); it aims to be a more regularly updated awesome deception list.

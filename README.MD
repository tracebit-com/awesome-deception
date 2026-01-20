# 🥷 Awesome Deception [![Awesome Deception](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

An awesome collection of articles, papers, conferences, guides, and tools relating to deception in cybersecurity. For a list of open source honeypots, see [awesome-honeypots](https://github.com/paralax/awesome-honeypots).

# Contents
- [Articles](#articles)
- [Research](#research)
- [Guides](#guides)
- [Talks](#talks)
- [Conferences](#conferences)
- [Communities](#communities)
- [Frameworks](#frameworks)
- [Related Lists](#related-lists)

> **NOTE** - This repo is a fork of a fork ([emilyanncr/awesome-deception](https://github.com/emilyanncr/awesome-deception) -> [tolgadevsec/Awesome-Deception](https://github.com/tolgadevsec/Awesome-Deception)) and aims to be a more regularly updated awesome deception list.

# Articles
- Explain Like I'm Five: [Poison Records](https://hackernoon.com/poison-records-acra-eli5-d78250ef94f) (2018) (Honeypots for Database Tables). (code) [Acra Poison Records](https://github.com/cossacklabs/acra-poison-records-demo).
- Deception Engineering: exploring the use of [Windows Service Canaries](https://www.nccgroup.com/us/research-blog/deception-engineering-exploring-the-use-of-windows-service-canaries-against-ransomware/) (2021) against ransomware. (code) [KilledProcessCanary](https://github.com/nccgroup/KilledProcessCanary).
- Valve used [secret memory access “honeypot”](https://arstechnica.com/gaming/2023/02/valve-used-secret-memory-access-honeypot-to-detect-40k-dota-2-cheaters/) (2023) to detect 40K Dota 2 cheaters.
  - [Discussion on Hacker News](https://news.ycombinator.com/item?id=34909218) on potential implementation techniques.  
- Introducing HASH: The HTTP Agnostic Software [Honeypot framework](https://securitylabs.datadoghq.com/articles/hash-honeypot-framework/) (2023) for creating HTTP low-interaction honeypots. (code) [HASH](https://github.com/DataDog/hash).
- Cloud [Active Defense](https://www.helpnetsecurity.com/2024/04/02/cloud-active-defense-open-source-cloud-protection/) (2024): Open-source cloud protection. (code) [Cloud Active Defense](https://github.com/SAP/cloud-active-defense).
- Thinkst’s It’s Baaack… [Credit Card Canarytokens](https://blog.thinkst.com/2024/12/its-baaack-credit-card-canarytokens-are-now-on-your-consoles.html) (2024) are now on your Consoles.
- UK’s NCSC on [building a nation-scale evidence base](https://www.ncsc.gov.uk/blog-post/building-a-nation-scale-evidence-base-for-cyber-deception) (2024) outlines the UK’s goals for large-scale deception deployment.
- [LLM Agent Honeypot](https://ai-honeypot.palisaderesearch.org/) (2024-2025) - a live experiment tracking AI-assisted attack activity in the wild.
- Wiz’s [HoneyBee threat research](https://www.wiz.io/blog/honeybee-threat-research) (2025) covers their open-source honeypot deployment tooling for misconfiguration and exploitation detection.
- GreyNoise on [deploying MCP honeypots](https://www.greynoise.io/blog/deploying-mcp-honeypots) (2025) shares results from observing MCP exploitation attempts.
- [Building a Military Honeypot](https://www.psu.edu/news/engineering/story/building-honeypot-fake-cameras-networks-deceive-military-adversaries) (2025) - Penn State’s effort to build deceptive camera and network environments for military use.
- [Deel/Rippling lawsuit](https://www.rippling.com/blog/lawsuit-alleges-12-billion-unicorn-deel-cultivated-spy-orchestrated-long-running-trade-secret-theft-corporate-espionage-against-competitor) (2025) - a public case where an insider was detected via a honeypot Slack channel.
- Grafana’s [security update on a GitHub workflow issue](https://grafana.com/blog/2025/04/27/grafana-security-update-no-customer-impact-from-github-workflow-vulnerability/) (2025) includes notes on deploying thousands of canaries.
- AWS on [improving active defense to empower customers](https://aws.amazon.com/blogs/security/how-aws-improves-active-defense-to-empower-customers/) (2025) covers its large-scale honeypot system.
- Grafana’s [canary tokens “unsung heroes” write-up](https://grafana.com/blog/2025/08/25/canary-tokens-learn-all-about-the-unsung-heroes-of-security-at-grafana-labs/) (2025) shares ROI and lessons learned.
- watchTowr Labs on [Canary Credentials in the wild](https://labs.watchtowr.com/stop-putting-your-passwords-into-random-websites-yes-seriously-you-are-the-problem/) (2025) highlights credential leakage via online tooling.
- UK’s NCSC on [cyber deception trials](https://www.ncsc.gov.uk/blog-post/cyber-deception-trials-what-weve-learned-so-far) (2025) shares early findings from UK-wide product trials.
- SpecterOps on [mapping deception with BloodHound OpenGraph](https://specterops.io/blog/2025/12/23/mapping-deception-with-bloodhound-opengraph/) (2025) details how to model deception coverage in BloodHound.
- Resecurity on [synthetic data for cyber deception and honeypots](https://www.resecurity.com/es/blog/article/synthetic-data-a-new-frontier-for-cyber-deception-and-honeypots) (2025) explores synthetic data to improve honeypot realism.
- Forescout on [a hacktivist attack targeting OT/ICS](https://www.forescout.com/blog/anatomy-of-a-hacktivist-attack-russian-aligned-group-targets-otics/) (2025) analyzes the incident, including honeypot use and defensive takeaways.

# Research
### Papers
- [Demystifying Deception Technology: A Survey](https://arxiv.org/abs/1804.06196) (2018) - survey of deception taxonomies, deployment models, and evaluation gaps.
- [Deception Techniques in Computer Security: A Research Perspective](https://dl.acm.org/doi/abs/10.1145/3214305) (2019) - broad survey of deception methods and research directions.
- [The Tularosa Study: An Experimental Design and Implementation to Quantify the Effectiveness of Cyber Deception](https://scholarspace.manoa.hawaii.edu/items/f05182cc-6460-410e-a750-e7c17f674be1) (2019) - HICSS study with 130+ red teamers, manipulating deception presence and awareness while tracking cognitive and physiological effects.
- [When Announcing Deception Technology Can Change Attacker Decisions](https://scholarspace.manoa.hawaii.edu/server/api/core/bitstreams/6c188375-03f6-4d66-afee-296308c9f2c0/content) (2024) - study on how disclosure of deception influences attacker behavior.
- [Prospect Theoretic Hypothesis Testing-based Cyber Deception](https://ieeexplore.ieee.org/abstract/document/11206237) (2025) - study on using prospect theory to shape deception during reconnaissance.
- [Towards bio-inspired cyber-deception: a case study of SSH and Telnet honeypots](https://backend.orbit.dtu.dk/ws/portalfiles/portal/398564454/ADND_Workshop_2025_Towards_bio_inspired_cyber_deception.pdf) (2025) - evaluates bio-inspired deception strategies in Cowrie SSH/Telnet honeypots.
- [Koney: A Cyber Deception Orchestration Framework for Kubernetes](https://arxiv.org/pdf/2504.02431) (2025) - orchestrates deception assets across Kubernetes clusters.
- [Applying game theory to deception](https://arxiv.org/pdf/2505.21244) (2025) - models attacker-defender dynamics using game-theoretic approaches.
- [Database Deception using Large Language Models](https://faculty.nps.edu/ncrowe/WAITI_Data_based_deception_paper.pdf) (2025) - applies LLMs to create deceptive database artifacts.
- [A Descriptive Model for Modelling Attacker Decision-Making in Cyber-Deception](https://arxiv.org/abs/2512.03641) (2025) - proposes a model of attacker engagement decisions under deception cues.
- [Agentic AI for Cyber Resilience: A New Security Paradigm and Its System-Theoretic Foundations](https://arxiv.org/abs/2512.22883) (2025) - argues for agentic resilience with cyber deception case studies.
- [SoK: Honeypots & LLMs, More Than the Sum of Their Parts?](https://arxiv.org/abs/2510.25939) (2025) - systematizes LLM-powered honeypot research and evaluation trends.
- [HoneyTrap: Deceiving Large Language Model Attackers to Honeypot Traps with Resilient Multi-Agent Defense](https://arxiv.org/abs/2601.04034) (2026) - proposes a deceptive LLM defense framework with multi-agent coordination, plus a progressive jailbreak dataset and new metrics for measuring misdirection and attacker cost. 

### Code Repositories
- [Evaluating Deception and Moving Target Defense with Network Attack Simulation](https://github.com/dfki-in-sec/NASIM-MTD)
- [Honeyquest](https://github.com/dynatrace-oss/honeyquest)
- [Knocking on Admin’s Door: Protecting Critical Web Applications with Deception](https://github.com/BillyPragSec/pageknocking)
- [SCANTRAP: Protecting Content Management Systems from Vulnerability Scanners with Cyber Deception and Obfuscation](https://github.com/dfki-in-sec/SCANTRAP)

# Guides
- [Birding Guide - Detect attackers without breaking the bank](http://canary-content.s3-website-us-east-1.amazonaws.com/documents/birding-guide.pdf)
- [Taxonomy and terminology](https://bluepillsecurity.com/blog/001_terms/) - terminology and definitions for cyber deception.

# Talks
- [Deception & Operations Planning Frameworks](https://www.youtube.com/watch?v=yIutY_X2FcU) (2025) - ShmooCon talk on a physical deception operation.
- [Applying Deception to the Attack Lifecycle](https://www.youtube.com/watch?v=vEHg9hRyJ9c) (2025) - Tim Pappa and Skylar Simmons (Walmart) on using deception across the attacker journey.
- [Sweet Deception: Mastering AWS Honey Tokens to Detect and Outsmart Attackers](https://www.youtube.com/watch?v=R75ZTBnUwXk) (2025) - Nick Frichette.
- [Continuous Integration / Continuous Deception: Trying my luck as a malicious maintainer](https://www.youtube.com/watch?v=ehmAy320R4A) (2025) - Benedikt Haußner.
- [Turning The Tables: Using Cyber Deception To Hunt Phishers At Scale](https://www.youtube.com/watch?v=78qnM_ZzpNc) (2024) - BSides Exeter.
- [Counter Deception: Defending Yourself in a World Full of Lies](https://www.youtube.com/watch?v=gHqDEMrqTjE) (2024) - DEF CON 32 (August 2024), Tom Cross and Greg Conti.
- [Mirage: Cyber Deception Against Autonomous Cyber Attacks](https://www.youtube.com/watch?v=S0ioMe-g0vk) (2024) - Black Hat USA 2024, Ron Alford and Michael Kouremetis.

# Conferences
- [Active Defense & Deception (AD&D)](https://adnd.work/) - Active conference, most recent event in 2025.
- [Honeynet Workshops](https://www.honeynet.org/workshops/) - Active conference, most recent event in 2025.

# Communities
- [/r/cyber_deception](https://www.reddit.com/r/cyber_deception/)
- [The Honeynet Project](https://www.honeynet.org/)

# Frameworks
- [MITRE Engage™](https://engage.mitre.org/)
  - [Engage](https://github.com/mitre/engage/tree/main) Data Repository.
- [MITRE D3FEND™](https://d3fend.mitre.org/)
  - [D3FEND](https://github.com/d3fend) Software Repositories.
- [Deception-as-Detection](https://github.com/0x4D31/deception-as-detection)

# Related Lists
- [awesome-honeypots](https://github.com/paralax/awesome-honeypots) - A thorough and fairly regularly updated list of open source honeypots.

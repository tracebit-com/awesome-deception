# 🥷 Awesome Deception [![Awesome Deception](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

An awesome list of resources on deception-based computer security with honeypots and honeytokens.

# Contents
- [Articles](#articles)
- [Communities](#communities)
- [Frameworks](#frameworks)
- [Guides](#guides)
- [Talks](#talks)
- [Conferences](#conferences)
- [Related Lists](#related-lists)
- [Research](#research)

> **NOTE** - This repo is a fork of a fork ([emilyanncr/awesome-deception](https://github.com/emilyanncr/awesome-deception) -> [tolgadevsec/Awesome-Deception](https://github.com/tolgadevsec/Awesome-Deception)) and aims to be a more regularly updated awesome deception list.

# Articles
- 🎮 Valve used [secret memory access “honeypot”](https://arstechnica.com/gaming/2023/02/valve-used-secret-memory-access-honeypot-to-detect-40k-dota-2-cheaters/) to detect 40K Dota 2 cheaters.
  - [Discussion on Hacker News](https://news.ycombinator.com/item?id=34909218) on potential implementation techniques.  
- 👿 Deception Engineering: exploring the use of [Windows Service Canaries](https://www.nccgroup.com/us/research-blog/deception-engineering-exploring-the-use-of-windows-service-canaries-against-ransomware/) against ransomware.
  - [KilledProcessCanary](https://github.com/nccgroup/KilledProcessCanary) Code Repository.
- ☠️ Explain Like I'm Five: [Poison Records](https://hackernoon.com/poison-records-acra-eli5-d78250ef94f) (Honeypots for Database Tables).
  - [Acra Poison Records](https://github.com/cossacklabs/acra-poison-records-demo) Demo Code Repository.
- 💳 It’s Baaack… [Credit Card Canarytokens](https://blog.thinkst.com/2024/12/its-baaack-credit-card-canarytokens-are-now-on-your-consoles.html) are now on your Consoles.
- 🍯 Introducing HASH: The HTTP Agnostic Software [Honeypot framework](https://securitylabs.datadoghq.com/articles/hash-honeypot-framework/) for creating HTTP low-interaction honeypots.
  - [HASH](https://github.com/DataDog/hash) Code Repository.
- ☁️ Cloud [Active Defense](https://www.helpnetsecurity.com/2024/04/02/cloud-active-defense-open-source-cloud-protection/): Open-source cloud protection
  - [Cloud Active Defense](https://github.com/SAP/cloud-active-defense) Code Repository.
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

# Communities
- [/r/cyber_deception](https://www.reddit.com/r/cyber_deception/)
- [/r/honeypot](https://www.reddit.com/r/honeypot/)
- [The Honeynet Project](https://www.honeynet.org/)

# Frameworks
- [MITRE Engage™](https://engage.mitre.org/)
  - [Engage](https://github.com/mitre/engage/tree/main) Data Repository.
- [MITRE D3FEND™](https://d3fend.mitre.org/)
  - [D3FEND](https://github.com/d3fend) Software Repositories.
- [Deception-as-Detection](https://github.com/0x4D31/deception-as-detection)

# Guides
- [Birding Guide - Detect attackers without breaking the bank](http://canary-content.s3-website-us-east-1.amazonaws.com/documents/birding-guide.pdf)

# Talks
- [Deception & Operations Planning Frameworks](https://www.youtube.com/watch?v=yIutY_X2FcU) (2025) - ShmooCon talk on a physical deception operation.
- [Applying Deception to the Attack Lifecycle](https://www.youtube.com/watch?v=vEHg9hRyJ9c) (2025) - Tim Pappa and Skylar Simmons (Walmart) on using deception across the attacker journey.
- [Sweet Deception: Mastering AWS Honey Tokens to Detect and Outsmart Attackers](https://www.youtube.com/watch?v=R75ZTBnUwXk) (2025) - Nick Frichette.
- [Continuous Integration / Continuous Deception: Trying my luck as a malicious maintainer](https://www.youtube.com/watch?v=ehmAy320R4A) (2025) - Benedikt Haußner.

# Conferences
- [Active Defense & Deception (AD&D)](https://adnd.work/) - Active conference, most recent event in 2025.
- [Honeynet Workshops](https://www.honeynet.org/workshops/) - Active conference, most recent event in 2025.

# Related Lists
- [awesome-honeypots](https://github.com/paralax/awesome-honeypots) - A thorough and fairly regularly updated list of open source honeypots.

# Research
### Papers
- [Demystifying Deception Technology: A Survey](https://arxiv.org/abs/1804.06196) (2018) - survey of deception taxonomies, deployment models, and evaluation gaps.
- [Deception Techniques in Computer Security: A Research Perspective](https://dl.acm.org/doi/abs/10.1145/3214305) (2019) - broad survey of deception methods and research directions.
- [The Tularosa Study: An Experimental Design and Implementation to Quantify the Effectiveness of Cyber Deception](https://scholarspace.manoa.hawaii.edu/items/f05182cc-6460-410e-a750-e7c17f674be1) (2019) - HICSS study with 130+ red teamers, manipulating deception presence and awareness while tracking cognitive and physiological effects.
- [When Announcing Deception Technology Can Change Attacker Decisions](https://scholarspace.manoa.hawaii.edu/server/api/core/bitstreams/6c188375-03f6-4d66-afee-296308c9f2c0/content) (2024) - study on how disclosure of deception influences attacker behavior.
  - [Tracebit commentary](https://tracebit.com/blog/canary-program-communication-secrecy-vs-discretion)
- [Prospect Theoretic Hypothesis Testing-based Cyber Deception](https://ieeexplore.ieee.org/abstract/document/11206237) (2025) - study on using prospect theory to shape deception during reconnaissance.
- [Koney: A Cyber Deception Orchestration Framework for Kubernetes](https://arxiv.org/pdf/2504.02431) (2025) - orchestrates deception assets across Kubernetes clusters.
- [Applying game theory to deception](https://arxiv.org/pdf/2505.21244) (2025) - models attacker-defender dynamics using game-theoretic approaches.

### Code Repositories
- [Evaluating Deception and Moving Target Defense with Network Attack Simulation](https://github.com/dfki-in-sec/NASIM-MTD)
- [Honeyquest](https://github.com/dynatrace-oss/honeyquest)
- [Knocking on Admin’s Door: Protecting Critical Web Applications with Deception](https://github.com/BillyPragSec/pageknocking)
- [SCANTRAP: Protecting Content Management Systems from Vulnerability Scanners with Cyber Deception and Obfuscation](https://github.com/dfki-in-sec/SCANTRAP)
### Groups and Laboratories
- [DFK IN - Cyber Resilience and Security](https://github.com/dfki-in-sec)
- [Purdue University - Deception Group](https://www.cerias.purdue.edu/site/deception/)
- [UK National Cyber Deception Laboratory](https://www.cyberdeception.org.uk/)

---
title: "Relating Security Engineering & Cybersecurity Standards"
classes: wide
tags:
	- cybersecurity
---

Cybersecurity is overwhelmed by standards, guidance, recommendations, and requirements.

What does this amount to?

Is this information in concert or in conflict?

Is this information actionable, practical, and useful for engineering secure systems?

To address these questions, I've created a publicly accessible relational database that organizes this information in a clear, navigable format.  

Explore the Airtable database: [Link](https://airtable.com/appIfMZL3Q2ydSFFk/shrT54RhWgP8oeoKI/tblzmbXeKrcG7FiFE/viwGxbuWwIFDXSEbu?blocks=biped4Irb3IzRtqjD)

<iframe class="airtable-embed" src="https://airtable.com/embed/appIfMZL3Q2ydSFFk/shrT54RhWgP8oeoKI?backgroundColor=purpleDusty" frameborder="0" onmousewheel="" width="100%" height="533" style="background: transparent; border: 1px solid #ccc;"></iframe>

For those who prefer the raw data, the .csv files and junction tables are available on GitHub.

Access the GitHub repository: [Link](https://github.com/thalient-ai/Security-Engineering)

Here is a brief walk through the chaos:

 - National Institute of Standards and Technology (NIST) 800-53 Revision
   5 provides **1,007** security controls but NIST 800-53B only recommends
   **370** security controls as a High baseline. Of the **1,007** security
   controls, **759** are Organizational and **394** are Technical (with some
   overlap).
 - United States Department of Defense CNSSI 1253 complicates the NIST
   800-53B control selection with a matrix of High, Moderate, and Low
   across Confidentiality, Integrity, and Availability. A "High, High,
   High" system now selects **573** security controls. CNSSI 1253 also
   removes exactly **1** out of the **1,007** security controls. Why?
 - If I want a Cyber Survivability system, then the CSEIG provides **10**
   Cyber Survivability Attributes that map to **215** security controls.
 - If I want a Cyber Resilient system, then NIST 800-160 Volume 2
   provides **14** techniques that map to **50** approaches that map to **186**
   security controls.
 - DISA breaks the **1,007** security controls into **3,816** Control
   Correlation Identifiers. These map to STIGs. Of the **3,816** CCIs, **3,301**
   are Policy and **693** are Technical (with some overlap). Only **18%** of
   CCIs are technical, whereas **39%** of security controls are technical.
 - ISO 27001:2022 provides **93** security controls that map to **205** of the
   NIST 800-53 security controls.
 - NIST 800-171 Revision 2 provides **110** security requirements for
   protecting CUI. Those **110** security requirements map to **127** security
   controls
 - NIST 800-172 supplement 800-171 with **39** security requirements that
   map to **91** security controls.
 - The MITRE ATT&CK framework provides **38** adversary tactics that map to
   **820** adversary techniques which map to **106** mitigations. The **106**
   mitigations are supplemented by an additional **115** candidate
   mitigations from NIST 800-160 Volume 2. The combined set of **221**
   mitigations map to **216** security controls.
 - The MITRE CAPEC contains **559** attack patterns which map to **188** ATT&CK
   techniques. The **559** attack patterns map to **336** of the **938** MITRE
   Common Weakness Enumerators (CWEs) which map to Common Vulnerability
   Enumerators (CVEs).

Do these mappings mean anything?

Are we focusing too much on compliance and too little on engineering?

I hope to make more data available in the coming weeks.
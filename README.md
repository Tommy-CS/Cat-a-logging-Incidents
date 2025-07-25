# Cat-a-logging Incidents
This repository documents my work on Lab 6 of Codepath's CYB102 course, which involved using Catalyst to manage and investigate three cybersecurity incidents: phishing, malware, and brute force.

## Overview
The goal of this lab was to simulate real-world incident response by:
- Creating incidents in Catalyst
- Investigating IoCs (Indicators of Compromise)
- Using tools like VirusTotal and AbuseIPDB
- Documenting findings and Lessons Learned
- Classifying each incident appropriately

## Tools Used
- Catalyst (self-hosted on Ubuntu VM)
- VirusTotal
- AbuseIPDB

## Screenshots
#### Here's what Catalyst looks like:
<img src="https://github.com/user-attachments/assets/68dcbf79-105d-4ada-8e25-b36586d81017" width="600"/>

---

#### Contents of ir_report_phising.md:
<img src="https://github.com/user-attachments/assets/73803522-96f1-4a61-9834-ca1a5a0d8e43" width="600"/>

---

#### Investigating the IP and hash (as you can see, they are malicious or compromised):
<img src="https://github.com/user-attachments/assets/d923b9d7-68e7-4aee-90b0-99cd14f7fadb" width="600"/> 

<img src="https://github.com/user-attachments/assets/7ee05ad0-c6d5-42a7-8f10-7afa515d2d6a" width="600"/> 

---

#### Creating an Incident:
<img src="https://github.com/user-attachments/assets/8122b885-1a74-46c4-a726-41ce0bd446d1" width="600"/>

---

#### Post-Incident Report
<img width="712" height="750" alt="image" src="https://github.com/user-attachments/assets/88f33577-5d0f-44e6-9fac-3554fa129b22" />

## Reflections
This lab gave me a better idea of how useful a platform like Catalyst is when you're dealing with real incidents. Instead of keeping everything in separate docs or spreadsheets, it was nice having one place to track what happened, who’s doing what, and all the evidence we found. It made things feel a lot more organized, especially when juggling multiple incidents.

Adding artifacts like IPs and hashes, then looking them up and logging notes, actually felt like real-world SOC work. It helped me see how important clear documentation and collaboration are during incident response. I could definitely see how a tool like this would make life easier when things get chaotic.

# ETHICS & RESPONSIBLE DISCLOSURE

This document defines the ethical rules and the responsible disclosure process for research conducted in this repository.

---

## Principles of Responsible Research

1. **Do no harm.** Do not perform actions that could disrupt services, expose private data, or harm users.  
2. **Work in controlled environments.** Use isolated testbeds, local copies of data, or sandboxed systems; never test on production or third-party services without explicit authorization.  
3. **Avoid sharing exploit details.** Do not publish code or instructions that enable bypassing authentication, anti-cheat, fraud protection, or other security measures. High-level descriptions are fine for learning; operational details that enable misuse are not.  
4. **Respect intellectual property.** Do not include or share proprietary assets, copyrighted data, or personally identifiable information.  
5. **Transparency and education.** Aim to produce materials that help defenders, educators, and learners understand risks and mitigation techniques.

---

## Responsible Disclosure Process

If you find a real security issue in a third-party service:

1. **Stop testing.** Immediately halt any active testing that could impact the target.  
2. **Document privately.** Take notes and create a private, concise report that includes:
   - A high-level description of the issue (no exploit steps).  
   - The potential impact and evidence (logs, timestamps, anonymized data).  
   - Steps to reproduce in a controlled lab (only if you have explicit permission from the owner).  
3. **Identify the correct contact.** Find the vendor’s security contact, official bug bounty program, or support channel. If none exist, look for `security@` or dedicated reporting guidelines.  
4. **Submit privately.** Send the report privately (email or the vendor’s secure portal). Use an encrypted channel if available.  
5. **Allow reasonable time.** Give the vendor sufficient time to acknowledge and fix the issue (commonly 30–90 days, depending on severity and policy).  
6. **Coordinate any public disclosure.** Only publish findings publicly after the vendor has fixed the issue or given explicit permission. When publishing, omit exploit details and focus on defensive lessons and mitigations.

---

## Contact / Reporting Template

When reporting an issue, you can use this template (fill in specifics and avoid step-by-step exploit instructions):



**Body:**

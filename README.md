# Instagram Impersonation OSINT Case Study

This repository documents a real-world inspired OSINT investigation into a suspected Instagram impersonation of a small business account. The case has been fully anonymized: names, usernames, visual identifiers, URLs, locations, and any other identifiable details have been removed or generalized.

The goal is to show the workflow, not to expose a specific organization or person. The original material was treated as case notes and rewritten into a clean portfolio project.

## Objectives

- Detect a suspected impersonation account.
- Analyze username similarity and possible typosquatting.
- Check whether the digital identity is consistent across public platforms.
- Assess the practical risk to the legitimate brand and its audience.

## Tools Used

- Maigret
- Sherlock, used as a secondary username-checking reference
- Manual OSINT techniques, including profile comparison, content review, and basic footprint validation

## Key Findings

- The suspected account used a username with a very small variation from the legitimate one. The difference was easy to miss at a quick glance.
- Public profile content appeared to be copied or closely replicated, including the account presentation, bio structure, and media style.
- Username intelligence returned many possible matches, but most did not show meaningful activity or identity continuity.
- No consistent public footprint was identified that would support the suspected account as an independent, established digital identity.
- Based on the observed indicators, the account showed a high likelihood of being an impersonation or clone profile.

## Why This Matters in Cybersecurity and Threat Intelligence

Social media impersonation is often treated as a reputation issue, but it can also support fraud, phishing, customer redirection, and trust abuse. A convincing clone account does not need advanced technical capability. It only needs to look familiar enough for users to interact with it.

For threat intelligence work, this kind of case is useful because it connects small indicators into a practical assessment: username variation, copied branding, weak external footprint, and platform behavior. None of those points is conclusive alone, but together they can support a clear escalation path.

## Skills Demonstrated

- OSINT collection and validation
- Threat analysis
- Pattern recognition
- Impersonation detection
- Username intelligence review
- False positive handling
- Professional reporting

## Repository Structure

```text
.
|-- README.md
|-- methodology.md
|-- report/
|   `-- report_redacted.md
|-- indicators/
|   `-- username_analysis.txt
|-- screenshots/
|   `-- example_redacted.txt
`-- disclaimer.md
```

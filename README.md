# Digital Impersonation OSINT Investigation

This repository documents an OSINT investigation based on a real case I worked through involving suspected digital impersonation on social media. The original case involved an Instagram business account clone, but the focus here is broader: identity consistency, impersonation indicators, and practical OSINT validation.

The case has been fully anonymized. Names, usernames, visual identifiers, URLs, locations, and any other identifiable details have been removed or generalized.

The goal here is to show the workflow and reasoning, not to expose a specific organization or person. I treated the original material as private case notes and rebuilt it into a clean portfolio version.

Italian version available here: [README.it.md](README.it.md)

## Objectives

- Detect a suspected impersonation account.
- Analyze username similarity and possible typosquatting.
- Check whether the digital identity is consistent across public platforms.
- Assess the practical risk to the legitimate brand and its audience.

## Tools Used

- Maigret
- Sherlock, used as a secondary username-checking reference
- Manual OSINT work: profile comparison, content review, and basic footprint validation

## Key Findings

- The suspected account used a username with a very small variation from the legitimate one. It was the kind of difference that is easy to miss.
- Public profile content looked copied or closely replicated, including the account presentation, bio structure, and media style.
- Username intelligence returned many possible matches, but most of them did not show useful activity or identity continuity.
- I did not find a consistent public footprint that supported the suspected account as an independent, established identity.
- Based on the combined indicators, the account had a high likelihood of being an impersonation or clone profile.

## Why This Matters in Cybersecurity and Threat Intelligence

Social media impersonation is often treated as only a reputation issue, but it can support fraud, phishing, customer redirection, and trust abuse. A convincing clone account does not need advanced technical capability. It just needs to look familiar enough for users to trust it.

For threat intelligence work, this kind of case is useful because the conclusion comes from small details put together: username variation, copied branding, weak external footprint, and platform behavior. None of those points is enough alone, but together they can support a clear escalation path.

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
|-- README.it.md
|-- methodology.md
|-- methodology.it.md
|-- report/
|   |-- report_redacted.md
|   `-- report_redacted.it.md
|-- indicators/
|   |-- username_analysis.txt
|   `-- username_analysis.it.txt
|-- screenshots/
|   |-- example_redacted.txt
|   `-- example_redacted.it.txt
|-- disclaimer.md
`-- disclaimer.it.md
```

# Phishing Email Analysis

## Overview
This project was completed as part of my Elevate Labs cybersecurity internship. It focuses on identifying suspicious email characteristics and understanding how phishing attacks attempt to trick users into revealing sensitive information or performing unsafe actions.

The project introduces a structured approach to email threat analysis and phishing awareness.

## Objectives
- Understand common phishing techniques.
- Identify suspicious email characteristics.
- Learn how to inspect email headers, sender details, links, and message content.
- Understand the role of phishing analysis in cybersecurity incident response.

## Tools and Technologies
Document the email-analysis tools and resources actually used during the investigation.

## Analysis Methodology

### 1. Sender Analysis
Examine the sender's email address and display name for inconsistencies, impersonation, or suspicious domains.

### 2. Subject and Message Content
Look for urgent requests, unexpected attachments, unusual wording, threats, and requests for confidential information.

### 3. Email Header Inspection
Where available, review header fields and authentication results such as SPF, DKIM, and DMARC to identify potential signs of spoofing.

### 4. Link Analysis
Inspect the visible link text and destination URL for misleading domains, unusual subdomains, misspellings, or unexpected redirects. Do not open suspicious links directly on a normal workstation.

### 5. Attachment Assessment
Identify unexpected or suspicious attachments. Do not execute unknown files. Use approved security tools or an isolated analysis environment when deeper inspection is necessary.

### 6. Risk Assessment
Summarize the evidence and determine whether the email appears legitimate, suspicious, or likely to be phishing. Explain the reasons for the assessment.

## Indicators of Phishing
- Sender addresses that imitate trusted organizations.
- Unexpected requests for passwords or financial information.
- Urgent or threatening language.
- Links whose destinations do not match the claimed organization.
- Unexpected attachments.
- Inconsistent authentication results or suspicious email headers.

These indicators should be evaluated together; a single indicator does not always prove an email is malicious.

## Findings
Document the actual observations from the email examined during the project.

Include:
- Suspicious sender or domain details, if found.
- Relevant header or authentication observations.
- Suspicious URLs or attachment characteristics.
- The evidence supporting the final assessment.
- Recommended defensive actions.

Do not invent findings or publish personal information from real emails.

## Recommended Defensive Actions
- Avoid clicking suspicious links or opening unexpected attachments.
- Verify unusual requests through a trusted communication channel.
- Report suspected phishing emails to the appropriate security team.
- Use email authentication and filtering controls.
- Enable multifactor authentication where available.

## Learning Outcomes
- Developed an understanding of phishing indicators.
- Learned a structured approach to email investigation.
- Improved awareness of email authentication and suspicious links.
- Understood the importance of evidence-based threat assessment.

## Disclaimer
This project is intended for educational and defensive cybersecurity purposes only. Suspicious emails and attachments should be handled in accordance with applicable security procedures.

## Author
**A. Rachel Joanne**

GitHub: [@racheljo11](https://github.com/racheljo11)

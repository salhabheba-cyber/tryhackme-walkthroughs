# Phishing Analysis Fundamentals – TryHackMe Walkthrough

## Objective
Understand how to analyze phishing emails by inspecting headers, sender information, and email content.

## Key Skills Demonstrated
- Email header analysis (Received, Reply-To, Return-Path)
- Identifying spoofed and phishing emails
- Sender IP investigation
- Domain and IP reputation checks

## My Process
1. Analyzed raw email headers to identify sender infrastructure
2. Compared From vs Reply-To to detect spoofing
3. Extracted sender IP from X-Originating-IP
4. Investigated IP and domain using WHOIS tools
5. Classified the email type (phishing vs legitimate)

## Tools Used
- WHOIS (DomainTools)
- Email header analysis
- OSINT investigation

## Key Takeaways
- Reply-To mismatch is a strong phishing indicator
- Headers often reveal hidden sender infrastructure
- Always verify IPs and domains using trusted sources
- SOC analysts must follow evidence, not assumptions

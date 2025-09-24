# Cybersecurity-Internship-Task-2
Phishing Email Analysis


# Cybersecurity Internship - Task 2: Phishing Email Analysis

# Email Header Analysis Report

## Sample Information
- **Email Source**: Simulated phishing email
- **Analysis Date**: [24/09/2025]
- **Tools Used**: MXToolbox, Google Admin Toolbox

## Header Analysis Findings

### Suspicious Elements:
1. **From Header Discrepancy**: 
   - Displayed: security-noreply@paypa1.com
   - Actual: Different IP origin detected

2. **SPF Check**: 
   - Result: Fail (Domain not authorized to send from detected IP)

3. **DKIM Signature**: 
   - Status: Missing or invalid

4. **Routing Anomalies**: 
   - Multiple hops through unverified servers
   - Geographical inconsistencies

### Technical Indicators:
- **Message-ID**: Irregular format inconsistent with legitimate PayPal emails
- **Received Fields**: Show routing through suspicious intermediate servers
- **Return-Path**: Different from From address


# Phishing Prevention Guide

## For Individuals:
1. **Verify sender addresses** carefully
2. **Hover over links** before clicking
3. **Use multi-factor authentication**
4. **Keep software updated**
5. **Report suspicious emails**

## For Organizations:
1. **Implement email filtering** solutions
2. **Conduct security awareness training**
3. **Enable DMARC, DKIM, and SPF**
4. **Regular phishing simulations**
5. **Incident response planning**

## Technical Controls:
- Email authentication protocols (SPF, DKIM, DMARC)
- Advanced threat protection
- URL filtering and rewriting
- Attachment sandboxing

## Task Overview
This repository contains my submission for Task 2 of the Cybersecurity Internship program. The objective was to analyze a phishing email sample and identify phishing characteristics.

## Tools Used
- **MXToolbox Header Analyzer**: Email header analysis
- **VirusTotal**: Domain and URL analysis
- **WHOIS Lookup**: Domain registration information
- **Google Admin Toolbox**: Additional header analysis

## Analysis Summary
- **Sample Source**: Simulated phishing email based on common PayPal phishing attempts
- **Phishing Indicators Identified**: 8 key indicators
- **Risk Level**: High - Sophisticated spoofing attempt
- **Social Engineering Tactics**: Urgency, authority, fear

## Key Findings
- Spoofed sender domain: paypa1.com (vs legitimate paypal.com)
- Suspicious verification link to unverified domain
- Use of urgent language and account suspension threats
- Lack of personalized information

## Files Structure
- `phishing-analysis/`: Detailed analysis reports and email sample
- `tools-used/`: Information about analysis tools and methodologies
- `documentation/`: Comprehensive answers and research
- `screenshots/`: Visual evidence of analysis process

## Learning Outcomes
- Developed skills in email header analysis
- Understood phishing tactics and social engineering
- Learned to use various email analysis tools
- Gained knowledge in email authentication protocols

## Author
[Nadeem Hasan]
Cybersecurity Intern

# FUTURE_CS_02 - Phishing Email Detection & Awareness Report

## Overview
This project presents a Phishing Email Detection & Awareness Report developed as part of the Furture Interns Cybersecurity Internship task two.

The goal of this project is to simulate the role of a security analyst by analyzing real-world phishing email samples, identifying common attack patterns, and creating an awareness document that can help users and organizations prevent phishing attacks.

Phishing is one of the most common cyber threats, and this project focuses on education, detection, and prevention, rather than hacking.

## Tools Used
- Google Message Header Analyzer  
- MXToolbox Email Header Analyzer  
- VirusTotal  
- Browser Developer Tools

## Methodology 
The analysis was conducted by first collecting phishing email samples from public repositories. The email headers were then examined using Google Message Header Analyzer and MXToolbox to identify authentication results such as SPF, DKIM, and DMARC. The sender domains and email routing paths were further investigated to determine the origin and legitimacy of the emails.

Additionally, any embedded URLs were analyzed using VirusTotal to assess whether they were malicious or suspicious. Common phishing indicators, including spoofed identities, urgent language, and suspicious links, were identified during the analysis. Each email was then classified based on its risk level.

Finally, all findings were documented in a structured report, and clear prevention and awareness guidelines were developed to help users recognize and avoid phishing attacks.

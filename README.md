# Email-security-awareness-lab
This repository contains a sample email simulating a security alert for unusual login activity, where a user is prompted to verify their identity after access from an unfamiliar device or location. It reflects a common real-world phishing scenario.

Overview
This repository contains a simulated phishing email used for cybersecurity analysis and SOC (Security Operations Center) training. The objective is to investigate the email using standard security techniques and identify potential threats.

Sample Email

**Subject:** Unusual Login Activity Detected  
**From:** Microsoft Security Team <info@libreriacies.es>  
**To:** sonyundefinedralph@gmail.com  

Dear User,  

We detected unusual login activity on your email account from a new device located outside your usual region.  

To prevent temporary suspension of your account, please verify your identity immediately by clicking the link below:  
https[:]//tinyurl[.]com/ypu5kfts  

If you do not verify your account within 24 hours, access to your mailbox may be restricted for security reasons.  

Please find attached a copy of the security report related to this activity for your reference.  

Thank you for helping us keep your account secure.  

Microsoft Security Team  
IT Support Desk  

---

Tasks to Complete

Using appropriate SOC investigation techniques and tools, perform the following:

1. **Identify Indicators of Compromise (IOCs)**  
   - Extract suspicious elements such as email addresses, domains, links, and language patterns.

2. **Investigate Email Addresses**  
   - Analyze the sender’s email and determine legitimacy or spoofing attempts.

3. **Analyze Sender’s Domain**  
   - Check domain reputation, registration details, and configuration (SPF, DKIM, DMARC).

4. **Examine Embedded URL (Safely)**  
   - Do NOT click the link.  
   - Use threat intelligence tools to determine if the URL is malicious or suspicious.

5. **Determine if Phishing**  
   - Provide a final verdict based on your findings and justify your conclusion.

---

Suggested Tools

- VirusTotal  
- WHOIS Lookup  
- URL Unshorteners  
- Email Header Analyzer  
- AbuseIPDB  

Disclaimer
This project is for educational purposes only. Do not use these techniques or samples for malicious activities.

Author
Sylvester Bassey
If you want, I can also create a **sample answer sheet (solution guide)** like a real SOC report — that’s something recruiters love to see in your portfolio.

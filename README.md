# OS-Hardening & Network Traffic Analysis

<h2>Description</h2>
This report analyzes a cybersecurity incident involving a malicious file delivered via HTTP traffic through the compromised website yummyrecipesforme.com. The attacker exploited a brute force vulnerability to gain administrative access, modifying the website’s source code to prompt unsuspecting users to download a file disguised as a browser update. When executed, the file redirected users to a fraudulent website (greatrecipesforme.com), causing performance issues on affected systems.
Key Findings:

# Attack Vector:
Exploitation of HTTP protocol at the application layer to distribute malicious files.
Brute force attack used to compromise the website’s admin credentials.
Evidence Collection:
Analyzed TCPDump logs to trace suspicious HTTP requests.
Examined the malicious file in a sandbox environment to understand its behavior and redirect patterns.

# Impact:
Users’ systems experienced slow performance post-download.
Administrative lockout for the website owner.
Attacker Methodology:
Injected code on the compromised website to deliver a fake browser update prompt.
Redirected HTTP traffic to a fraudulent website post-malware execution.

# Remediation Actions:
Implemented password policy enhancements, disallowing the reuse of default or prior passwords.
Enforced frequent password updates to minimize the risk of credential compromise.
Deployed two-factor authentication (2FA) to add an extra layer of security against brute force attacks.

 This detailed report demonstrates my ability to document and analyze security incidents, assess vulnerabilities, and recommend practical mitigation strategies.
 
Keywords: #Cybersecurity #IncidentResponse #HTTPAttack #MalwareAnalysis #BruteForceProtection #2FA
<br />

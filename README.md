Dear all,
 
Please find the email comm for the by CVE-2024-8929 as below:


Hi [insert],

You are receiving this threat notification as we have preliminarily identified your PHP Instance to be potentially vulnerable to by CVE-2024-8929. If this is accurate and belongs to you, we highly recommend patching immediately as this vulnerability in the PHP could enable attackers to leak partial content of the heap through a heap buffer over-read.

Affected Versions:
•	8.1. before 8.1.31
•	8.2. before 8.2.26
•	8.3. before 8.3.14

Summary:
 
CVE-2024-8929 is an Information Disclosure vulnerability in PHP that could allow attackers to connect to a fake MySQL server or tampering with network packets.

This bug can then allow them to initiate a SQL Query, and abuse the function when parsing MySQL fields packets.

A public proof-of-concept (PoC) exploit has been released, which poses a threat by making it more likely for attackers to exploit vulnerabilities, potentially allowing them to leak sensitive information.

Additionally, other PHP critical vulnerabilities like out-of-bounds flaw (CVE-2024-8932) and integer overflow flaw (CVE-2024-11236) have been assigned with CVSS v3 score of 9.8, which can lead to serious impact like arbitrary code execution.
 
Recommendations:
 
PHP has released an official advisory and patches to remediate the vulnerabilities. We advise you to patch as soon as possible to eliminate the potential threat of exploitation. 

https://github.com/php/php-src/security
 
For SOC Only: We will continue to monitor the external perimeter for potential exploitation of this vulnerability and inform you if we identify malicious activity.

Please feel free to contact us if you would like to gain a better understanding on the vulnerability and how we can support you. 


Best regards,
Herbert Kwok | PwC | Risk Assurance
PricewaterhouseCoopers
22/F Prince's Building, Central, Hong Kong
tel +852 2289 3463
herbert.mh.kwok@hk.pwc.com | http://www.pwchk.com



From: Herbert MH Kwok (HK - ASR) 
Sent: Tuesday, November 26, 2024 3:37 PM
To: HK Cyber Threat Operations <darklab.cto@hk.pwc.com>
Cc: CN-HK cyberthreatoperations <cn-hk.cyberthreatoperations@hk.pwc.com>; Darklab Threat Intelligence <darklab.cti@hk.pwc.com>
Subject: [CVE] PoC Released for PHP Fake MySQL Server Connection or Network Tampering Leading to Arbitrary Code Execution (CVE-2024-8929)

Date of Evaluation	26/11/2024
Vulnerability CVE ID	CVE-2024-8929
Age of Vulnerability	Last 3 Days
CvSS v3 Impact Score	Medium/Low - 0.1 - 6.9
SOC Product Coverage	Known to be used by SOC Client(s)
Initial Access	No - Authenticated
Impact of Exploitation	Remote Code Execution
Attack Complexity	High
Privileges Required	Normal User Privileges
User Interaction	No
Attack Vector	Adjacent
Proof-of-Concept	Yes
Exploited in the Wild	No Exploitation in the Wild
Threat Discussion - Dark Web	No
Threat Discussion - Social Media	No
Threat Discussion - OSINT	No
Patch or Mitigation Available	No
Potentially Vulnerable Victims in Hong Kong, Macau, China, Malaysia (Shodan)?	No
EPSS Score at time of evaluation	0.04%
	
	
Final Score	5.81
Outcome	Email Communications
Date of listing	22/11/2024
Name of Vulnerability	PoC Released for PHP Fake MySQL Server Connection or Network Tampering Leading to Arbitrary Code Execution
Product 	php
Impacted Versions	Versions prior to 8.1.31, 8.2.26, and 8.3.14.
Vendor Advisory	https://github.com/php/php-src/security/advisories/GHSA-h35g-vwh6-m678

Third Party Advisory	https://securityonline.info/php-patches-multi-flaws-including-cve-2024-8932-cvss-9-8-urges-immediate-update/

	
Manual Override?	No
Reason of Override	 

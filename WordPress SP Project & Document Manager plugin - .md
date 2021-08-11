# Exploit Title: WrodPress SP Project & Document Manager plug-in, the settings page has multiple reflective cross-site scripting vulnerabilities
# Exploit Author: Thinkland Security Team
# Vendor Homepage: https://wordpress.org/plugins/sp-client-document-manager/
# Version :  V 4.25
# Vulnerability Type: Cross-site Scripting
# Tested on Windows 10 、XAMPP
# Vulnerability proof：  
1. Click settings
![image](https://github.com/BigTiger2020/word-press/blob/main/xss-4.png)  
2. Input content,click save
![image](https://github.com/BigTiger2020/word-press/blob/main/xss-5.png)  
3.Modify the data request packet and insert the xss payload
![image](https://github.com/BigTiger2020/word-press/blob/main/xss-6.png)  
4.Click settings again
![image](https://github.com/BigTiger2020/word-press/blob/main/xs.gif)  



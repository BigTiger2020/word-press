# Exploit Title: WrodPress SP Project & Document Manager plug-in, the settings page has multiple types of cross-site scripting vulnerabilities scripting vulnerabilities
# Exploit Author: Thinkland Security Team
# Vendor Homepage: https://wordpress.org/plugins/sp-client-document-manager/
# Version :  V 4.25
# Vulnerability Type: Cross-site Scripting
# Tested on Windows 10 、XAMPP
# Vulnerability proof：  
1. Click settings
![image]()  
2. Input content,click save
![image]()  
3.Modify the data request packet and insert the xss payload
![image]()  
4.Click settings again
![image]()  



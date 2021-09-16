# Exploit Title: WordPress Plugin Simple Job Board——Stored Cross-Site Scripting
# Exploit Author: Thinkland Security Team
# Date: 16/09/2021
# Vendor Homepage: https://wordpress.org/plugins/simple-job-board/
# Version :  V 2.9.4
# Vulnerability Type: Stored Cross-Site Scripting
# Tested on Windows 10 、XAMPP
# Vulnerability proof：  
1. Job Board  >> Add New >> Add title and enter the XSS payload "<img src=1 onerror=alert(/xss/)>"
![image]()  
2. Click Publish,You will observe that the payload successfully got stored into the database and when you are triggering the same functionality at that time JavaScript payload is executing successfully and we are getting a pop-up.
![image]()  
3.Vulnerability proof:
![image]()  
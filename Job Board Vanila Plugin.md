# Exploit Title: WrodPress  Job Board Vanila Plugin——Stored Cross-Site Scripting
# Exploit Author: Thinkland Security Team
# Vendor Homepage: https://wordpress.org/plugins/job-board-vanilla/
# Version :  V 1.0
# Vulnerability Type: Stored Cross-Site Scripting
# Tested on Windows 10 、XAMPP
# Vulnerability proof：  
1. Jobs 》Add New 》Job Fields 》Location ,insert the xss payload <img src=1 onerror=alert(3)>
![image]()  
2. Click Save Draft,go to  http://192.168.50.200/wordpress/?post_type=job&p=3269&preview=true
![image]()  
3.Vulnerability proof:
![image]()  
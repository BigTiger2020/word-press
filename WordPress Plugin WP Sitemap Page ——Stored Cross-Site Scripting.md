# Exploit Title: WordPress Plugin WP Sitemap Page——Stored Cross-Site Scripting
# Exploit Author: Thinkland Security Team
# Date: 07/09/2021
# Vendor Homepage: https://wordpress.org/plugins/wp-sitemap-page/
# Version :  V 1.6.4
# Vulnerability Type: Stored Cross-Site Scripting
# Tested on Windows 10 、XAMPP
# Vulnerability proof：  
1. Navigate to Settings >> WP Sitemap Page >> Settings and enter the XSS payload into the "How to display the posts" Input field.on
![image](https://github.com/BigTiger2020/word-press/blob/main/WP%20Sitemap%20Page-1.png)  
2. Click Save changes,You will observe that the payload successfully got stored into the database and when you are triggering the same functionality at that time JavaScript payload is executing successfully and we are getting a pop-up.
![image](https://github.com/BigTiger2020/word-press/blob/main/WP%20Sitemap%20Page-2.png)  
3.Vulnerability proof:
![image](https://github.com/BigTiger2020/word-press/blob/main/WP%20Sitemap%20Page.gif)  

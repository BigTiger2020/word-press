# Exploit Title: WrodPress Plugin GeoDirectory——Stored Cross-Site Scripting
# Exploit Author: Thinkland Security Team
# Vendor Homepage: https://wordpress.org/plugins/geodirectory/
# Version :  V 2.1.1.2
# Vulnerability Type: Stored Cross-Site Scripting
# Tested on Windows 10 、XAMPP
# Vulnerability proof：  
1. go to http://192.168.50.200/wordpress/wp-admin/admin.php?page=gd-settings&tab=general&section=location
![image](https://github.com/BigTiger2020/word-press/blob/main/1.png)  
2. Click Save changes,In the default_location_latitude parameter, insert the xss payload "prompt(/xss/)"
![image](https://github.com/BigTiger2020/word-press/blob/main/2.png)  
3.Visit again http://192.168.50.200/wordpress/wp-admin/admin.php?page=gd-settings&tab=general&section=location
![image](https://github.com/BigTiger2020/word-press/blob/main/3.png)  
4.Vulnerability proof:
![image](https://github.com/BigTiger2020/word-press/blob/main/xss1.gif)  



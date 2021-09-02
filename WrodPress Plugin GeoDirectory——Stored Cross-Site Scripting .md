# Exploit Title: WrodPress Plugin GeoDirectory——Stored Cross-Site Scripting
# Exploit Author: Thinkland Security Team
# Vendor Homepage: https://wordpress.org/plugins/geodirectory/
# Version :  V 2.1.1.2
# Vulnerability Type: Stored Cross-Site Scripting
# Tested on Windows 10 、XAMPP
# Vulnerability proof：  
1. go to http://192.168.50.200/wordpress/wp-admin/admin.php?page=gd-settings&tab=general&section=location
![image]()  
2. Click Save changes,In the default_location_latitude parameter, insert the xss payload "prompt(/xss/)"
![image]()  
3.Visit again http://192.168.50.200/wordpress/wp-admin/admin.php?page=gd-settings&tab=general&section=location
![image]()  
4.Vulnerability proof:
![image]()  



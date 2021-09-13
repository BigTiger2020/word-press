# Exploit Title: WordPress Plugin TablePress 1.14 - CSV Injection 
# Exploit Author: Thinkland Security Team
# Vendor Homepage: https://wordpress.org/plugins/tablepress/
# Version :  V 1.14
# Vulnerability Type: CSV Injection 
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

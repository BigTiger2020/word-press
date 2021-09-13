# Exploit Title: WordPress Plugin TablePress 1.14 - CSV Injection 
# Exploit Author: Thinkland Security Team
# Vendor Homepage: https://wordpress.org/plugins/tablepress/
# Version :  V 1.14
# Vulnerability Type: CSV Injection 
# Tested on Windows 10 、XAMPP
# Vulnerability proof：  
1. Navigate to TablePress → Add New → Enter Table Name and Description (If You want this is Optional) → Select Number of Rows and Columns → Click on Add Table
![image](https://github.com/BigTiger2020/word-press/blob/main/cvs1.png)  
2. Now in Table Content Input Field Enter CSV Injection Payload：- @SUM(1+9)*cmd|' /C calc'!A0 → Click on Save Changes
![image](https://github.com/BigTiger2020/word-press/blob/main/cvs2.png)  
3.Now go to All Table in TablePress select our entered table → Click on Export → Select CSV as an Export Format → Click on Download Export File
![image](https://github.com/BigTiger2020/word-press/blob/main/cvs3.png)  
4.Open the exported CSV file you will see that CSV Injection got Successfully Executed.
![image](https://github.com/BigTiger2020/word-press/blob/main/cvs4.png)  

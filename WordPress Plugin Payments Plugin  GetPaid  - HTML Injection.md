# Exploit Title: WordPress Plugin Payments Plugin | GetPaid  - HTML Injection
# Exploit Author: Thinkland Security Team
# Date: 07/09/2021
# Vendor Homepage: https://wordpress.org/plugins/invoicing/
# Version :  V 2.4.6
# Vulnerability Type: HTML Injection
# Tested on Windows 10 、XAMPP
# Vulnerability proof：  
1. Navigate to GetPaid > Payment Forms
2. Click on "Add New" in the Payment Form page
3. Add a title and Click on Billing Email
4. You can see the "Help Text" field on the left hand side.
5. Add the below HTML code into the "Help Text" Field.payload:<img src="https://tse2-mm.cn.bing.net/th/id/OIP-C.EqYveV1oWg-VhMZAIJjRBQHaE8?w=259&amp;h=180&amp;c=7&amp;r=0&amp;o=5&amp;pid=1.7" height="200px" width="200px">
6. You will observe that the HTML code has successfully got stored into the database and executed successfully and we are getting an Image at the right hand side.
![image](https://github.com/BigTiger2020/word-press/blob/main/html.png)  

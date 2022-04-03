# Secureflag Writeup


**Authorization Bypass in Admin Functionalities**

Solution Method 

if login.is_user_admin():

Reason , calling the to check whether user is admin or not from the 

OWASP Top 10:2021 in Python
 
 SQL Injection 

Solution

sql_statement = "Select username FROM username=? and password_hash=?"
c.execute(sql_statement, (username, password_hash))

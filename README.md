# Test Cases

Below are some Test Cases examples 

---------------------

**Title:** 
Test login with modified URL address

**Description:**
Check if the login functionality and URL site addresses works independently. 

**Steps to reproduce:** 
1. Go to: www.website.com/login
2. Change the “login” word from above address with word “myaccount”, the new address will be  www.website.com/myaccount 
3. Acces the new URL address 

**Expected result:** User shouldn’t be able to login and must appear on a page with an error message. 

**Test data:** Address will be  www.website.com/myaccount 

---------------------

**Title:**
Test login with correct credentials and active/selected/tick  “Remember Me” option.

**Description:**
Check if the login functionality saves the user data after disconnect and displays them when the user wants to connect.

**Steps to reproduce:**
1. Go to  www.website.com/login
2. Complete fields with test data and select (tick=bifeaza) “Remember me” option.
3. Press login button.
4. After a few seconds, disconnect the account.
5. See if the login fields are already completed with test data at the login section. 

**Expected result:**
User should be able to login without completing the login fields if the “Remember Me” option is active. 

**Test data:** 
User: Radu and Pass: 123456

---------------------

next test

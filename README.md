# TestCases 

Below are some test cases that I wrote working on my projects.

---------------------------------------------------------------
**Title**
Test login with correct credentials

**Description:**
Check if the login works when a person uses the correct credentials.

**Steps to reproduce**
1. Go to website: https://home.openweathermap.org/users/sign_in 
2. Add correct user/pass
3. Observe if user can login by pressing the "submit" button

**Expected Result**
User should be able to login and is redirected to website having the account loaded.

**Test Data**
User: adrianperianu@hotmail.com
Pass: prodigy@8486
---------------------------------------------------------------

**Title**
Test login with incorrect credentials

**Description:**
Check if the login works when a person uses the incorrect credentials.

**Steps to reproduce**
1. Go to website: https://home.openweathermap.org/users/sign_in 
2. Add incorrect user/pass
3. Observe if user can login

**Expected Result**
User should not be able to login.

**Test Data**
User: adip2022
Pass: 123456

-----------------------------------------------------------------

**Title**
Test login without credentials

**Description:**
Check if the login works without typing credentials.

**Steps to reproduce**
1. Go to website: https://home.openweathermap.org/users/sign_in 
2. Skip adding user/pass
3. Observe if user can login

**Expected Result**
User should not be able to login without typing the credentials.

-------------------------------------------------------------------
**Title**
The "Remember Me" checkbox on the login page should be functional 


**Description:**
Check if the "Remember Me" checkbox works when returning to login action after logging in with correct credentials.

**Steps to reproduce**
1. Go to website: https://home.openweathermap.org/users/sign_in 
2. Add correct user/pass and tick the "Remember me" checkbox
3. Observe if user can login
4. After successfully loggin in, user logs out
5. Go again to login page and check if your user and password are filled in
6. Observe if user can login again successfully

**Expected Result**
User should be able to login successfully without having to retype the credentials if the step of loggin in has formerly been performed correctly by ticking the "Remember me" checkbox. 

**Test Data**
User: adrianperianu@hotmail.com
Pass: prodigy@8486

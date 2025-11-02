# Use Case: UC-01 — Login / Logout

**Use Case ID:** UC-01  
**Name:** Login and Logout  
**Actor:** Registered User (Customer)  
**Preconditions:** User account exists (username/password), Internet available.  
**Basic Flow:**
1. User opens https://www.saucedemo.com
2. User enters username and password
3. User clicks "Login"
4. System validates credentials and redirects to inventory page
5. user clicks "Logout" and returns to Login page

**Alternate Flow :** 
- Invalid credentials -> show "Username and Password do not match" error.

**Exception Flow :** 
- Server down -> show "service unavailable" message.

**Postcondition :**
- User is logged in and can access the inventory
- After Logout the session ends.

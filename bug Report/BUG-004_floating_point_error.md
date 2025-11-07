# BUG-004 — Floating-Point Price Calculation Error

**Bug ID:** BUG-004 
**Title:** Incorrect price total due to floating-point calculation error  

**Environment:**  
- Browser: Chrome  
- OS: Windows 11 
- Website: https://www.saucedemo.com  
- Page: Checkout → Overview  

**Steps:**  
1. Login to https://www.saucedemo.com  
2. Add **Sauce Labs Backpack ($29.99)**  
3. Add **Sauce Labs Bolt T-Shirt ($15.99)**  
4. Proceed to **Cart → Checkout**  
5. Enter required user info and continue  
6. Observe the **Item Total** under "Checkout: Overview"

**Actual Result:**
- Item total displays as a long floating number:  
  **$59.980000000000004**

**Expected Result:**
- Item total should display correct formatted value:  
  **$59.98**

**Severity:** Major  

**Priority:** High  
(Billing-related bugs must be fixed immediately.)

**Evidence:**  evidence/screenshots/BUG-004.png

# TC-007 - Remove item from cart  

**ID:** TC-007  

**Title:** Verify that the user can remove items from the shopping cart  

**Preconditions:**  
- User is logged in successfully
- User is on `/cart.html` page 
- At least one item has been added to the cart 

**Steps:** 
1. Navigate to the Cart page (`/cart.html`) 
2. click on the **Remove** button for any item 
3. Observe the cart page and car icon in header

**Expected Result:** 
- The selected product is removed from the cart page.  
- The cart icon in the header updates to reflect the new item count.

**Actual Result:** 
- **Remove** button works correctly 
- The product is removed and the cart icon updates as expected.  

**Status:** Pass  

**Evidence:** evidence/screenshots/TC-007-pass.png 
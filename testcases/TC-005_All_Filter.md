# TC-005 - All filters are working

**ID:** TC-005

**Title:** All filters are working  

**Precondition:** 
- User account exists and successfully log in  
- Inventory page load and products and filter option visible

**Steps:**  
1. Navigate to the inventory page 
2. Navigate to the `Filter` dropdown option (top right)
3. Hover over the filter icon (funnel symbol)  
    - Observe that the cursor changes to the `Hand Pointer` (indicating clickability)  
4. Click on the filter icon  
5. Dropdown menu expand to show options  
6. click on `Filter Text` “Price (low to high)” 
7. Observe filter behavior on products 
8. Click and observe all filters one by one   

**Expected Result:** 
- Filter dropdown is visible  
- All filter options are present and visible after clicking `filter icon` (funnel symbol)  
- Products are displaying according to the filter  

**Actual Result:** 
- Inventory page load and Filter dropdown is visible  
- Clicking on the `filter icon` does not open the dropdown, even though the hand cursor appears.
- Clicking on the `filter text` opens the dropdown successfully.
- Filters are working on products 

**Status:** Fail  

**Evidence:**  evidence/screenshots/TC-005-fail.png          

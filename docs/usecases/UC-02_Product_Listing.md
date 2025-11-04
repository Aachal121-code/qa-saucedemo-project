# Use case: UC-02 - Product Listing

**Use Case ID:** UC-02    
**Name:** Product Listing    
**Actor:** Customer    
**Preconditions:** 
- User account exists and can successfully log in.   
- Application server is up and running.        

**Basic Flow:**  
1. User opens https://www.saucedemo.com
2. User login with valid credentials
3. System redirects to the inventory page
4. All available products are display with name, price and image.
5. User uses the *filter* dropdown to sort products
6. User can click "Add to Cart" from the product listing

**Alternate Flow:**  
- Products page doesn't load fully or product list appears blank.  
- Sorting/Filter option is not responding to user selection  

**Exceptional Flow:**  
- Server down or network issue -> show "Service Unavailable" message.    
- Session timeout before loading products.   

**Postcondition:**  
- User can view and interact with product listing successfully   
- selected items are added to the cart
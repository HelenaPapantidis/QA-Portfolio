**Note**
 This document is presenting bug reports made for AcademyBugs app.

----------------------------------------------------------------------------------------------------------------------------------
ID \- 1

**Title**: Product image not fully displayed on product detail view in desktop

**Description**: In the product detail view for "Dark Grey Jeans" the product image does not fully display. There is visible white space on the right side, indicating improper alignment or scaling.

**Environment**: Desktop,  OS Windows 11, Chrome Version 129

**Preconditions**: Chrome browser is opened  
**Steps to reproduce** :

1. Navigate to [https://academybugs.com](https://academybugs.com).  
2. Click on the "Find Bugs" link in the navigation bar.  
3. Click on the product "Dark Grey Jeans."  
   

**Expected result**: The product image should fully occupy the designated image display area, with no extra white space on the sides.

**Actual result:** There is a white space on the right side of the image.

**Severity**: low  
**Priority**: medium

**Attachment**: [screenshot](https://drive.google.com/file/d/1EcL3s407R8-QxzwtAUslXfEvSOm2M9AY/view?usp=sharing)

---

ID \- 2

**Title**: Product short description and full description not in English on product detail page

**Description**: When the user opens the product details page the short description and full description of the product are displayed in a language other than English.

**Environment**: Desktop,  OS Windows 11, Chrome Version 129

**Preconditions**: Chrome browser is opened  
**Steps to reproduce** :

1. Navigate to [https://academybugs.com](https://academybugs.com).  
2. Click on the "Find Bugs" link in the navigation bar.  
3. Click on the product “Flamingo Tshirt”

   

   

   

**Expected result**: The short description and full product description should be displayed in English, matching the language of the rest of the site.

**Actual Result:** The short description and full product description are displayed in a different language (not English).

**Severity**: medium  
**Priority**: hgh

**Attachment**: [screenshot](https://drive.google.com/file/d/1YvpW-Ye-yEOxnzZS0udxP0_Xa_YyACvW/view?usp=sharing)

---

ID \- 3

**Title**: Page Becomes Unresponsive When Selecting Number of Results on Results Page

**Description**: The page freezes and becomes unresponsive when attempting to change the number of displayed results using the buttons on the top left. This issue occurs consistently and impacts usability, preventing users from interacting with the site effectively.

**Environment**: Desktop, OS Windows 11, Chrome Version 129

**Preconditions**: Chrome browser is opened  
**Steps to reproduce** :

1. Navigate to [https://academybugs.com](https://academybugs.com).  
2. Click on the "Find Bugs" link in the navigation bar.  
3. Click on the button 10 at the top left of the results list.  
     
   

**Expected result**: The page should display the selected number of results smoothly, updating the content as per the selected option.

**Actual result:** The page freezes when clicking on the button to change the number of results 

**Severity**: critical  
**Priority**: high

**Attachment**: [Video](https://jam.dev/c/6aff3cc3-4375-4dd1-8e94-c30989ce6840)

---

ID \- 4

**Title**: Grand Total in Cart Exceeds Sum of Product Prices by $100

**Description**: The grand total displayed in the cart and checkout is consistently $100 more than the sum of all product prices added to the cart. This discrepancy impacts the accuracy of order totals.

**Environment**: Desktop, OS Windows 11, Chrome Version 129

**Preconditions**:

*  Browser Google Chrome is open.  
* At least one product is available for purchase.

**Steps to reproduce** :

1. Navigate to [https://academybugs.com](https://academybugs.com).  
2. Click on the "Find Bugs" link in the navigation bar.  
3. Click on the available product for purchase.  
4. Click button “ADD TO CART”

**Expected result**: The grand total in the cart should accurately reflect the sum of all products’ prices.  
**Actual result:** The grand total in the cart is $100 more than the calculated sum of all individual product prices in the cart.

**Severity**: Critical  
**Priority**: high

**Attachment**: [screenshot](https://drive.google.com/file/d/1sziv7DNq7EY_RMpqoNJEN2lXF7sp7TrF/view?usp=sharing)

---

ID \- 5

**Title**: Filter by Price Does Not Apply the Selected Price Range on Product Pages

**Description**: When a user selects a price range from the "Filter by Price" section, whether on the product details page or the Store Menu, the page reloads, but the products displayed do not update to reflect the selected price range, all products are still visible. 

**Environment**: Desktop, OS Windows 11, Chrome Version 129

**Preconditions**: Chrome browser is opened  
**Steps to reproduce** :

1. Open [https://academybugs.com](https://academybugs.com).  
2. Click the "Find Bugs" link in the navigation bar.  
3. Open any product page.  
4. On the right side menu, find the "Filter by Price" section.  
5. Select any of the price ranges.

   

   

**Expected result**: A list of products in the selected price range should be displayed.

**Actual result:** Products displayed are not filtered by the selected price range.

**Severity**:Medium  
**Priority**: medium  
**Issue Type:** Functional  
**Repro Rate** : Every Time

**Attachment**: screenshot

---

ID \- 6

**Title**: Billing address section loads infinitely

**Description**: When navigating to the Billing Address section on the Dashboard, the page continuously loads without displaying any billing information. 

**Environment**: Desktop, Windows 11, Chrome Version 129

**Preconditions**: Chrome browser is opened  
User have account and is logged into

**Steps to reproduce** :

1. Navigate to [https://academybugs.com](https://academybugs.com).  
2. Click on the "Find Bugs" link in the navigation bar.  
3. Open any product.  
4. At the bottom of the right side menu, select "Dashboard."  
     
   

**Expected result**: The "Billing Address" section should display the appropriate billing information.  
**Actual result:** The "Billing Address" section continuously loads and does not display any information.

**Severity**: low  
**Priority**: medium

**Attachment**: [screenshot](https://drive.google.com/file/d/1Evw_vihn2IVnoUNI0ICebgKNmNSc2kKk/view?usp=sharing) ,  [video](https://screenrec.com/share/gKHSz9pVBA) 


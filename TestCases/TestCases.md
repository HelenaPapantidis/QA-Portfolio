**Test Case 01**   
**Title: Verify adding a new Local Benefit Group with valid data with maximum characters input.**  
**Priority:** **High**  
**Preconditions:** 

* The user is logged in with an HR account.

| Steps | Test Steps | Test Data | Expected Results |
| :---: | ----- | ----- | ----- |
| 1\. | Click on “Company Benefits” from the sidebar. | / | Company Benefit Group page is displayed. |
| 2\. | Click on button “+” Add Local Benefit Group. | / | Add Local Benefit Group form is opened and displayed. |
| 3\. | Fill in the "Name" field valid data | Enter the maximum number of  characters (30) that contain lowercase and uppercase letters, special characters, and number  | Entered data is displayed. |
| 4\. | Click the arrow in the "Category" dropdown menu | / | The dropdown menu expands and displays available options. |
| 5\. | Select category from the dropdown list | / | The selected category is selected and displayed in the “Category” field. |
| 6\. | Enter valid data in the "Summary" field | Enter the maximum number of  characters (90) that contain lowercase and uppercase letters, special characters, and number  | The Summary field accepts and displays entered data. |
| 7\. | Fill in the "Description" field with valid data | Enter the maximum number of  characters (90) that contain lowercase and uppercase letters, special characters, and number  | The Description field accepts the input and displays it. |
| 8\. | Click the "Photo" field  | /  | The file explorer opens to allow file selection. |
| 9\. | Select and upload an image file with valid dimension and format. |  Choose an image file (.png, .jpg, .jpeg format, 500\*500px dimensions and a landscape orientation. ) | The image is uploaded successfully, and a preview is displayed. |
| 10\. | Click the "Create" button | / | Successful message " New Benefit Group 'name' successfully added" is displayed and company benefit is displayed on the list. |

**Test Case 02**    
**Title: Verify the behavior of  Filter Functionality for Budget for option 75% \- 100%***  
**Priority:** **low**  
**Preconditions:** 

* The user is logged in with an HR account.  
* There is at least one employee registered in the system.  
* The "Filter by Budget Percentage" feature must be available in the "Employees" module.

| Steps | Test Steps | Test Data | Expected Results |
| :---: | ----- | ----- | ----- |
| 1\. | Click on Employees on the side bar. | / | Page with employees informations is displayed. |
| 2\. | Click on the arrow on the Filter by used budget percentage. | / | Dropdown is expanded with options. |
| 3\. | Click option |  75%-100% | Option 75%-100% is selected, data for the budget range of employees is shown in this range. |

**Test Case 03**   
**Title: Verify user can subscribe to benefit from Browse benefits**  
**Priority:** **High**  
**Preconditions:** 

* The user is logged in with a Member account.  
* The user has at least 100 tokens in their account.  
* There is a created Benefit Group “Dexyco”

| Steps | Test Steps | Test Data | Expected Results |
| :---: | ----- | ----- | ----- |
| 1\. | Click on the Dexyco card from "Browse Benefits". | / | The Dexyco popup window  opens displaying types of vouchers. |
| 2\. | Scroll  down to the "Univerzalni vaučer" section. | / | "Univerzalni vaučer" section is visible. |
| 3\. | Fill in the field ‘for value’ (RSD). |  RSD 1000 | The Vaucher value is shown in the field, the number of tokens is displayed according to voucher price in RSD and the price with VA is shown. The quantity field shows 1\. |
| 4\. | Click the "+" button next to the quantity field. | / | Quantity increases by 1 (now showing 2), and the price with VAT is automatically recalculated. |
| 5\. | Click button Redeem | / | A message is displayed: "You have successfully subscribed to the benefit." |
| 6\. | Click on the My Benefits  | / | Dexyco benefits are shown in the user's benefits section. |

Based on the pairwise technique for filter functionality, two test cases have been selected according to the analytics data, highlighting the most frequently used filter options.

**Test Case 04**  
**Title: Verify the system behavior when applying filters by Sort, Location, Benefit Type, and Category.**  
**Priority:** **medium**  
**Preconditions:** 

* The user is logged in with a member account.  
* The system has valid benefit groups available for filtering.  
* The necessary data (like benefit groups, locations, types, and categories) exists in the system.

| Steps | Test Steps | Test Data | Expected Results |
| :---: | ----- | ----- | ----- |
| 1\. | Click on the “Sort Benefit Groups” dropdown. | / | The Sort Benefit Groups dropdown is expanded and options are visible |
| 2\. | Select the desired sorting option | “Newest” | Option “newest” is selected and displayed, descending order is displayed. Benefits on the Browse Benefit page are shown in descending order from newest card.  |
| 3\. | Click on the Location dropdown . | / | Location dropdown is expanded and options are visible |
| 4\. | Click on the option “Novi Sad” | “Novi Sad”’ | Novi Sad option is selected and displayed. Benefits on the Browse Benefit page are shown from the newest benefit  in descending order and from the selected location.  |
| 5\. | Click on the Filter Benefit Type dropdown. | / | The Filter Benefit Type dropdown is expanded and options are visible. |
| 6\. | Click on the option “one time” | “One time” |  The “One Time’ option is selected and displayed ,Benefits on the Browse Benefit page are filtered and shown in descending order  from the selected location and with the chosen benefit type. . |
| 7\. | Check checkbox “Health” | / | The “Health”  checkbox is selected, benefits on the Browse Benefit page are displayed  in descending order and from the selected location, benefit type and only from the  “Health” category.  |

**Test Case 05**  
**Title: Verify the system behavior when applying filters by Sort, Location, Benefit Type, and Category.**  
**Priority:** **medium**  
**Preconditions:** 

* The user is logged in with a member account.  
* The system has valid benefit groups available for filtering.  
* The necessary data (like benefit groups, locations, types, and categories) exists in the system.

| Steps | Test Steps | Test Data | Expected Results |
| :---: | ----- | ----- | ----- |
| 1\. | Click on the “Sort Benefit Groups” dropdown. | / | The Sort Benefit Groups dropdown is expanded and options are visible. |
| 2\. | Select the sorting option | “Best Rated” | Option is selected and displayed, Benefits on the Browse Benefit page are shown sorted in descending order based on rating, with the newest card appearing first. |
| 3\. | Click on the “Location” dropdown . | / | Location dropdown is expanded and options are visible. |
| 4\. | Select the location  | “Beograd” | Location option is selected and displayed. Benefits on the Browse Benefit page are shown from the newest benefit  in descending order and from the selected location. |
| 5\. | Click on the Filter Benefit Type dropdown. | / | The Filter Benefit Type dropdown is expanded and options are visible. |
| 6\. | Click on the option “Monthly” | “Monthly” | The “One Time’ option is selected and displayed ,Benefits on the Browse Benefit page are filtered and shown in descending order  from the selected location and with the chosen benefit type. |
| 7\. | Check checkboxes “Sport & Recreation”, “Wellness & Wellbeing” | “Sport & Recreation”, “Wellness & Wellbeing | The selected categories are applied. Benefits are filtered by location, benefit type, categories, and sorted in descending order.  |



# saucedemo-qa-project
## objective
To test saucedemo.com website in all aspects like, functional,UI , Input validation,error Handling, to improve the Quality of the application.
## Scope
The scope of this project includes Login page, inventory page, browse products, cart, checkout.
## Types of Testing
* Functional
* UI
* Negative testing
* Edge cases
* Cross-browser consideration
## Test Environment
### Browsers: 
1. Google Chrome 151.0.7922.72
2. Firefox 153.0.1
### OS: Windows 11
### Device: Laptop
## Test Data:
Test data used has been included in each test case separately.
## Test Cases
| Subject         | Description                                                                                                                                         |
|-----------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| Test Case ID    | TC_001                                                                                                                                              |
| Test Case Title | Verify Login functionality with valid username with leading and trailing spaces and valid password.                                                 |
| Test Data       | Username:" standard_user " <br> Password: "secret_sauce"<br/>                                                                                       | 
| Steps to follow | 1. Open Google Chrome.<br> 2. Go to https://www.saucedemo.com/ .<br>3. Enter username and Password.<br>4. Click Login.<br>5. Observe error message. |
| Expected Result | The page should be redirected to the inventory page of user.      |
|Actual Result|Error message "Epic sadface: Username and password do not match any user in this service" is displayed.|
|Status| Failed                                                                                                                                              |


| Subject         | Description                                                                                                                                         |
|-----------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| Test Case ID    | TC_002                                                                                                                                              |
| Test Case Title | Verify Login functionality of locked out user.                                                                                   |
| Test Data       | Username:"locked_out_user" <br> Password: "secret_sauce"<br/>                                                                                       |
| Steps to follow | 1. Open Google Chrome.<br> 2. Go to https://www.saucedemo.com/ .<br>3. Enter username and Password.<br>4. Click Login.<br>5. Observe error message. |
| Expected Result | Appropriate error message for a locked out user should be displayed.                                                                                |
|Status| Passed                                                                                                                                              |


| Subject         | Description                                                                                                                                                                                                                |
|-----------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Test Case ID    | TC_003                                                                                                                                                                                                                     |
| Test Case Title | Verify Add to cart functionality.                                                                                                                                                                                          |
| Test Data       | Username:"standard_user" <br> Password: "secret_sauce"<br/> Product1: Sauce Labs Onesie.<br> Product2: Sauce Labs Bike Light.                                                                                              |
| Steps to follow | 1. Open Google Chrome.<br> 2. Go to https://www.saucedemo.com/ .<br>3. Enter username and Password.<br>4. Click Login.<br>5. Among products, click add to cart Product1 and Product2.<br>6. Go to cart and verify products. |
| Expected Result | The cart should have Product1 and Product2.                                                                                                                                                                                |
| Status          | Passed   |


| Subject         | Description                                                                                                                                                                                                                                                                                           |
|-----------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Test Case ID    | TC_004                                                                                                                                                                                                                                                                                                |
| Test Case Title | Verify sorting functionality of products in inventory page.                                                                                                                                                                                                                                           |
| Test Data       | Username:"standard_user" <br> Password: "secret_sauce"<br/>                                                                                                                                                                                                                                           |
| Steps to follow | 1. Open Google Chrome.<br> 2. Go to https://www.saucedemo.com/ .<br>3. Enter username and Password.<br>4.Click Login.<br>5. Click on filter option and click 4 options(Name(A to Z), Name(Z to A), Price(low to high), Price(high to low)) one by one.<br>6 Check product list order on every option. |
| Expected Result | The order of products should change appropriate to the option.                                                                                                                                                                                                                                        |
| Status          | Passed                                                                                                                                                                                                                                                                                                |


| Subject         | Description                                                                                                                                                                                                                                                                                                                                    |
|-----------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Test Case ID    | TC_005                                                                                                                                                                                                                                                                                                                                         |
| Test Case Title | Verify checkout functionality.                                                                                                                                                                                                                                                                                                                 |
| Test Data       | Username:"standard_user" <br> Password: "secret_sauce"<br/> firstname: "standard" <br>lastname: "user" <br>pincode:"543223"                                                                                                                                                                                                                     |
| Steps to follow | 1. Open Google Chrome.<br> 2. Go to https://www.saucedemo.com/ .<br>3. Enter username and Password.<br>4. Click Login.<br>5. Add any two items to the cart.<br>6. Go to cart and click on checkout.<br> 7. Fill the form with valid first name, last name and pincode.<br>8. Click on continue.<br>9. Check final details and click on finish. | 
| Expected Result | Order dispatched message should be displayed.                                                                                                                                                                                                                                                                                                  | 
| Status          | Passed                                                                                                                                                                                                                                                                                                                                         |


## Risk Assesment
| Functionality | Risk Level | Test Scenario                                                  |
|---------------|------------|----------------------------------------------------------------|
| Login         | High       | User cannot login with valid credentials                       |
| Login         | High       | User with Invalid Credentials can Login Successfully           |
| Login         | Low        | Error message for Input validation is not appropriate          |
|Inventory| High       | Add to cart button not responding                              |
|Inventory| High       | Images and Title of products is different from actual products. |
|Cart| Medium     | Only one item of same type can be placed order.                |
|Cart| Low        | Empty cart still user can proceed to checkout                  |
|Cart|High| Products in the cart is different from the products selected.  |
|Cart|Low| Incorrect number of products in the cart.                      |
|Check-out|High| Mandatory checkout form fields is not accepting input.         |
|Check-out|High| Sum of products price is Incorrect.                            |
|Check-out|High|After finishing checkout, no response of payment successful displayed.|

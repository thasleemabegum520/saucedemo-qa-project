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
| Expected Result | The page should be redirected to the inventory page of user.                                                                                        |
|Status| Failed                                                                                                                                              |


| Subject         | Description                                                                                                                                         |
|-----------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| Test Case ID    | TC_002                                                                                                                                              |
| Test Case Title | Verify Login functionality of locked out user.                                                                                   |
| Test Data       | Username:"locked_out_user" <br> Password: "secret_sauce"<br/>                                                                                       |            
| Steps to follow | 1. Open Google Chrome.<br> 2. Go to https://www.saucedemo.com/ .<br>3. Enter username and Password.<br>4. Click Login.<br>5. Observe error message. |
| Expected Result | Appropriate error message for a locked out user should be displayed.                                                                                |
|Status| Passed                                                                                                                                              |

| Subject         | Description                                                                                                                                                                                                                 |
|-----------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Test Case ID    | TC_003                                                                                                                                                                                                                      |
| Test Case Title | Verify Add to cart functionality.                                                                                                                                                                                           |
| Test Data       | Username:"standard_user" <br> Password: "secret_sauce"<br/> Product1: Sauce Labs Onesie.<br> Product2: Sauce Labs Bike Light.                                                                                               |            
| Steps to follow | 1. Open Google Chrome.<br> 2. Go to https://www.saucedemo.com/ .<br>3. Enter username and Password.<br>4. Click Login.<br>5. Among products, click add to cart Product1 and Product2.<br>6. Go to cart and verify products. |
| Expected Result | The cart should have Product1 and Product2.                                                                                                                                                                                 |
| Status          | Passed                                                                                                                                                                                                                      |                                                                                                                                                                                   |

| Subject         | Description                                                                                                                                                                                                                                                                                           |
|-----------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Test Case ID    | TC_004                                                                                                                                                                                                                                                                                                |
| Test Case Title | Verify filter functionality in inventory page.                                                                                                                                                                                                                                                        |
| Test Data       | Username:"standard_user" <br> Password: "secret_sauce"<br/>                                                                                                                                                                                                                                           |            
| Steps to follow | 1. Open Google Chrome.<br> 2. Go to https://www.saucedemo.com/ .<br>3. Enter username and Password.<br>4.Click Login.<br>5. Click on filter option and click 4 options(Name(A to Z), Name(Z to A), Price(low to high), Price(high to low)) one by one.<br>6 Check product list order on every option. | 
| Expected Result | The order of products should change appropriate to the option.                                                                                                                                                                                                                                        |
| Status          | Passed                                                                                                                                                                                                                                                                                                |

| Subject         | Description                                                                                                                                                                                                                                                                                                                                    |
|-----------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Test Case ID    | TC_005                                                                                                                                                                                                                                                                                                                                         |
| Test Case Title | Verify checkout functionality.                                                                                                                                                                                                                                                                                                                 |                                    |
| Test Data       | Username:"standard_user" <br> Password: "secret_sauce"<br/>                                                                                                                                                                                                                                                                                    |            
| Steps to follow | 1. Open Google Chrome.<br> 2. Go to https://www.saucedemo.com/ .<br>3. Enter username and Password.<br>4. Click Login.<br>5. add any two items to the cart.<br>6. go to cart and click on checkout.<br> 7. Fill the form with valid first name, last name and pincode.<br>8. Click on continue.<br>9. Check final details and click on finish. | 
| Expected Result | Order dispatched message should be displayed.                                                                                                                                                                                                                                                                                                  | 
| Status          | Passed                                                                                                                                                                                                                                                                                                                                         |

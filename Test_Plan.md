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
| Subject         | Description                                                                                                                                 |
|-----------------|---------------------------------------------------------------------------------------------------------------------------------------------|
| Test Case ID    | TC_001                                                                                                                                      |
| Test Case Title | Verify Login functionality with valid username with leading and trailing spaces and valid password.                                         
| Test Data       | Username:" standard_user " <br> Password: "secret_sauce"<br/>                                                                               |            
| Steps to follow | 1. Open Google Chrome.<br> 2. Go to http://saucedemo.com .<br>3.Enter username and Password.<br>4.Click Login.<br>5. Observe error message. 
| Expected Result | The page should be redirected to the inventory page of user.                                                                                |
|Status|Failed |


| Subject         | Description                                                                                                                                 |
|-----------------|---------------------------------------------------------------------------------------------------------------------------------------------|
| Test Case ID    | TC_002                                                                                                                                      |
| Test Case Title | Verify Login functionality with valid username and valid password.                                                                          
| Test Data       | Username:"locked_out_user" <br> Password: "secret_sauce"<br/>                                                                               |            
| Steps to follow | 1. Open Google Chrome.<br> 2. Go to http://saucedemo.com .<br>3.Enter username and Password.<br>4.Click Login.<br>5. Observe error message. 
| Expected Result | Appropriate error message for a locked out user should be displayed.    
|Status|Passed|

| Subject         | Description                                                                                                                                |
|-----------------|--------------------------------------------------------------------------------------------------------------------------------------------|
| Test Case ID    | TC_003                                                                                                                                     |
| Test Case Title | Verify Add to cart functionality.                                        
| Test Data       | Username:"standard_user" <br> Password: "secret_sauce"<br/>                                                                               |            
| Steps to follow | 1. Open Google Chrome.<br> 2. Go to http://saucedemo.com .<br>3.Enter username and Password.<br>4.Click Login.<br>5. Observe error message. 
| Expected Result | The page should be redirected to the inventory page of user.                                                                               

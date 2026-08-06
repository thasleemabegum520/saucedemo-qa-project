<p align='center'>BUG REPORTS</p>


| Subject            | Description                                                                                                                                                      |
|--------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Bug ID             | BUG-001                                                                                                                                                          |
| Bug Summary        | Verify Login functionality with valid username with leading and trailing spaces and valid password.                                                              |
| Test Data          | Username:" standard_user " <br> Password: "secret_sauce"<br/>                                                                                                    | 
| Steps to Reproduce | 1. Open Google Chrome.<br> 2. Go to https://www.saucedemo.com/ .<br>3. Enter username and Password.<br>4. Click Login.                                           |
| Expected Result    | User should login sucessfully.                                                                                                                                   |
| Actual Result      | Error message "Epic sadface: Username and password do not match any user in this service" is displayed.                                                          |
| Severity           | High                                                                                                                                                             |
| Proirity           | Medium                                                                                                                                                           |
| Evidence           | [Before Login]![Beforelogin_usernamewith_space.png](Screenshots/Beforelogin_usernamewith_space.png) [After Login]![Afterlogin_usernamewith_space.png](Screenshots/Afterlogin_usernamewith_space.png) |

| Subject             | Description                                                                                                                                                         |
|---------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Bug ID              | BUG-002                                                                                                                                                             |
| Bug Summary         | Verify Login functionality with valid username and invalid password.                                                                                                |
| Test Data           | Username:"standard_user" <br> Password: "secret"<br/>                                                                                                               | 
| Steps to Reproduce  | 1. Open Google Chrome.<br> 2. Go to https://www.saucedemo.com/ .<br>3. Enter username and Password.<br>4. Click Login.<br>5. Observe the 'X' symbol on both Fields. |
| Expected Result     | The password field should have 'X' mark as it is incorrect.                                                                                                         |
| Actual Result       | username is wrongly identified as invalid. Have 'X' mark on username field also.                                                                                    |
| Severity            | Low                                                                                                                                                                 |
| Proirity            | Low                                                                                                                                                                 |
| Evidence Screenshot | ![Wrong_password.png](Screenshots/Wrong_password.png)                                                                                                               |


| Subject            | Description                                                                                                                                                                |
|--------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Bug ID             | BUG-003                                                                                                                                                                    |
| Bug Summary        | Verify Sorting option in the inventory page.                                                                                                                               |
| Test Data          | Username:"standard_user" <br> Password: "secret_sauce"<br/>                                                                                                                | 
| Steps to Reproduce | 1. Open Google Chrome.<br> 2. Go to https://www.saucedemo.com/.<br>3. Enter username and Password.<br>4. Click Login.<br>5. Click on the dropdown arrow on inventory page. |
| Expected Result    | Sorting options should be displayed on dropdown.                                                                                                                           |
| Actual Result      | Nothing happens when clicking dropdown arrow. Though filter icon, and Name(A to Z) sort field is working properly.                                                         |
| Severity           | Low                                                                                                                                                                        |
| Proirity           | Low                                                                                                                                                                        |
| Evidence Video     | ![Sorting_Arrow.mp4](Screenshots/Sorting_Arrow.mp4)                                                                                                                        |


| Subject            | Description                                                                                                                                                              |
|--------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Bug ID             | BUG-004                                                                                                                                                                  |
| Bug Summary        | Add to cart is not working for some products of one user.                                                                                                                |
| Test Data          | Username:"problem_user" <br> Password: "secret_sauce"<br/>Product1: "Sauce Labs Bolt T-Shirt"                                                                            | 
| Steps to Reproduce | 1. Open Google Chrome.<br> 2. Go to https://www.saucedemo.com/.<br>3. Enter username and Password.<br>4. Click Login.<br>5. Click add to cart of Product1.               |
| Expected Result    | Product1 should be added into the cart.                                                                                                                                  |
| Actual Result      | Nothing happens when clicking Add to Cart option of product1. This result is reflecting  similarly with following products ["Sauce Labs Fleece Jacket","T-Shirt (Red)"]. |
| Severity           | High                                                                                                                                                                     |
| Proirity           | High                                                                                                                                                                     |
| Evidence Video     |  ![Add_tocart_bug.mp4](Screenshots/Add_tocart_bug.mp4)


| Subject            | Description                                                                                                                                                                                                                 |
|--------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Bug ID             | BUG-005                                                                                                                                                                                                                     |
| Bug Summary        | Checkout form is not accepting keyboard keys in lastname field for one user.                                                                                                                                                |
| Test Data          | Username:"problem_user" <br> Password: "secret_sauce"<br/>  Product1: "Sauce Labs Backpack" <br> First Name: "problem" <br/> Last Name: "user"                                                                              | 
| Steps to Reproduce | 1. Open Google Chrome.<br> 2. Go to https://www.saucedemo.com/.<br>3. Enter username and Password.<br>4. Click Login.<br>5. Add product1 to Cart<br>6. Go to Cart and click Checkout.<br>7. Enter First Name and Last Name. |
| Expected Result    | The Form should accept the keys of keyboard for Last Name field.                                                                                                                                                            |
| Actual Result      | The Last Name field is not responding. instead First Name is getting modified with one character which is typed most recently.                                                                                              |
| Severity           | High                                                                                                                                                                                                                        
| Proirity           | High                                                                                                                                                                                                                        |
| Evidence Video     |![checkout_form.mp4](Screenshots/checkout_form.mp4)

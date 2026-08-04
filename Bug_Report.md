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

| Subject             | Description                                                                                                                                                                |
|---------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Bug ID              | BUG-002                                                                                                                                                                    |
| Bug Summary         | Verify Login functionality with valid username having leading and trailing spaces and valid password.                                                                      |
| Test Data           | Username:"qwe" <br> Password: "secret_sauce"<br/>                                                                                                                          | 
| Steps to Reproduce  | 1. Open Google Chrome.<br> 2. Go to https://www.saucedemo.com/ .<br>3. Enter username and Password.<br>4. Click Login.<br>5. Observe the 'X' symbol on the password field. |
| Expected Result     | Error message of invalid username should be displayed.                                                                                                                     |
| Actual Result       | Password is wrongly identified as invalid.                                                                                                                                 |
| Severity            | Low                                                                                                                                                                        |
| Proirity            | Low                                                                                                                                                                        |
| Evidence Screenshot | ![Afterlogin_valid_password.png](Screenshots/Afterlogin_valid_password.png)|


| Subject             | Description                                                                                                                                                                |
|---------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Bug ID              | BUG-003                                                                                                                                                                    |
| Bug Summary         | Verify Login functionality with valid username having leading and trailing spaces and valid password.                                                                      |
| Test Data           | Username:"qwe" <br> Password: "secret_sauce"<br/>                                                                                                                          | 
| Steps to Reproduce  | 1. Open Google Chrome.<br> 2. Go to https://www.saucedemo.com/ .<br>3. Enter username and Password.<br>4. Click Login.<br>5. Observe the 'X' symbol on the password field. |
| Expected Result     | Error message of invalid username should be displayed.                                                                                                                     |
| Actual Result       | Password is wrongly identified as invalid.                                                                                                                                 |
| Severity            | Low                                                                                                                                                                        |
| Proirity            | Low                                                                                                                                                                        |
| Evidence Screenshot |
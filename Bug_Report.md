<p align='center'>BUG REPORTS</p>


| Subject            | Description                                                                                                            |
|--------------------|------------------------------------------------------------------------------------------------------------------------|
| Bug ID             | BUG-001                                                                                                                |
| Bug Summary        | Verify Login functionality with valid username with leading and trailing spaces and valid password.                    |
| Test Data          | Username:" standard_user " <br> Password: "secret_sauce"<br/>                                                          | 
| Steps to Reproduce | 1. Open Google Chrome.<br> 2. Go to https://www.saucedemo.com/ .<br>3. Enter username and Password.<br>4. Click Login. |
| Expected Result    | User should login sucessfully.                                                                                         |
| Actual Result      | Error message "Epic sadface: Username and password do not match any user in this service" is displayed.                |
| Severity           | High|
|Proirity|Medium|
|Evidence|[Before Login](Screenshots/Beforelogin_usernamewith_space.png)|


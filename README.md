
Step 1: Create a database called jobportal and import everything from jobportal(sql) file. 

```php
//Your db.php Mysql Config
$servername = "localhost";
$username = "root";
$password = "";
$dbname = "jobportal";
```

Step2: Now you login as candidate with following details

```php
Email: test1@user.com
Password: 123456
//Note1: There are 10 candadates users all with same password-123456
//Note2: All Password are encrpyted through code so you CANNOT change password directly from database.
```

Step3: Now you login as employer with following details

```php
Email: test1@employer.com
Password: 123456
//Note1: There are 5 Companies account all with same password-123456
//Note2: All Password are encrpyted through code so you CANNOT change password directly from database.
```

Step4: Now you login as Admin with following details

```php
Username: admin
Password: 123456
//Note: Password is not encrpyted from code so you CAN change directly from database.
```

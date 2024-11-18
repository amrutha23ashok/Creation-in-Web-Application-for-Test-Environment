 # CREATION IN WEB APPLICATION FOR TEST ENVIRONMENT
## AIM
To Creation in Web Application for Test Environment.
## PROBLEM STATEMENT
Creating a web application for a test environment is essential to provide developers and testers with a dedicated platform to simulate, test, and validate software functionalities. The challenge lies in building an easy-to-use, scalable, and efficient application that supports realistic testing scenarios, automates workflows, and ensures smooth collaboration while minimizing setup and maintenance efforts.

## ALGORITHM
 ### Steps 1:
 tep 1:
Launch an EC2 instance in AWS using an Amazon Linux 2 AMI with a Security Group allowing HTTP and SSH traffic.

### Step 2:
Connect to the instance using SSH and install a web server like Apache

### Step 3:
Create a simple HTML file in the server's default directory with basic content for testing.

### Step 4:
Access the instance's public IP in a browser to verify the HTML page is displayed.

## COMMANDS
### webserver
To install httpd:
```
yum install httpd -y
```
To enable and start httpd :
```
systemctl enable httpd
systemctl start httpd
```
Create a simple HTML page :
```
cd /var/www/html
```
test.php
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>MY FIRST PHP!</title>
</head>
</body>
</html>
```

## OUTPUT
### REG NUMBER:212223040048
### NAME:GOGINENI BIDHISHA
### TERMINAL:
![image](https://github.com/user-attachments/assets/dbe8f71f-5e06-46a0-9771-dfa23dd75c14)
![image](https://github.com/user-attachments/assets/9db6f614-fc84-4b7b-8370-2377dcc40466)
![image](https://github.com/user-attachments/assets/f612842a-538f-4a5c-ab26-cfe58a987dac)
### WEBPAGE:
![image](https://github.com/user-attachments/assets/a1078832-13f0-45ab-afdc-1fad332d0ec9)

## RESULT
Thus the web application for test environment has successfully been created and executed.
 

  



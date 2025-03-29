# SECURITY-TESTING-FOR-WEB-APPLICATIONS

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: NEELA SWAPNA

*INTERN ID*: CT6WTQY

*DOMAIN*: SOFTWARE TESTING

*DURATION*: 6WEEKS

*MENTOR*: NEELA SANTHOSH

##
The above code uses Selenium WebDriver for automating security testing in web applications. ChromeDriver is used to interact with the Chrome browser. The program tests for SQL Injection (SQLi) by injecting malicious SQL queries into login fields and checks if unauthorized access is granted. It also tests for Cross-Site Scripting (XSS) by injecting JavaScript payloads into input fields to see if scripts execute. In real-time, this approach is used in e-commerce, banking, and social media platforms to identify vulnerabilities in login forms, comment sections, and search bars, helping developers secure web applications against cyber threats.


# OUTPUT

Scenario 1: Application is Vulnerable (SQL Injection & XSS Found)
If the web application does not have proper security measures in place, the expected output would be:

"SQL Injection Vulnerability Found!
XSS Vulnerability Found!"

Scenario 2: Application is Secure (No SQLi & No XSS Found)
If the application has security measures like prepared statements and input validation, the expected output would be:

"No SQL Injection Vulnerability Detected.
No XSS Vulnerability Detected."

Scenario 3: Partial Vulnerability (Only XSS Found)
If the login form is secure but the comment section is vulnerable, you might see:

"No SQL Injection Vulnerability Detected.
XSS Vulnerability Found!"

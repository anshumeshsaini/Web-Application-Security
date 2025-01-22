Here is a summary of web application testing methods:

### 1. **Functional Testing
An application is tested for correctness: 
- **Unit Testing:** Individual components are tested.
- **Integration Testing:** Interaction between the units is checked.
- **System Testing:** Test the whole system.
- **Smoke & Sanity Testing:** Roughly checks and some key functionalities are checked. 

### 2.   Non-Functional Testing
Evaluation of the performance, security, usability, etc.: 
-  Performance Testing: Load, stress, and scalability testing.
-  Security Testing: Vulnerabilities identify, such as SQL injection, cross site scripting etc.
- **Usability Testing:** Checks for user-friendliness.
- **Compatibility Testing:** Tests cross-browser/device functionality.

### 3. **UI/UX Testing**
- **UI Testing:** Checks the visual elements.
- **UX Testing:** Checks the overall user experience.

### 4. **Regression Testing
Ensures that new updates don't break existing functionality.

### 5. **Acceptance Testing
Confirms that the app meets business requirements:
- **Alpha Testing:** Internal testing.
- **Beta Testing:** External user feedback.

### 6. **API Testing
Tests the application's APIs for functionality, security, and performance.

### 7. **Database Testing
Validates data integrity, security, and query performance.

### 8. **Cross-Browser/Device Testing**
Ensures compatibility across different browsers and devices.

### 9. **Security Testing**
Simulates attacks (e.g., penetration testing) to find vulnerabilities.

### 10. **Exploratory Testing**
Testers explore the app without predefined test cases to find unexpected issues.

### 11. **End-to-End Testing**
Simulates real-world user scenarios to test the complete workflow.

### Best Practices
- Test early and often.
- Automate repetitive tests (e.g., regression).
- Use real devices for cross-browser/device testing.
  Create test cases that are clear and repeatable.

### Tools
- Selenium, Postman, JMeter, Burp Suite, BrowserStack, TestComplete for the different types of testing.

This approach ensures comprehensive evaluation of functionality, security, performance, and user experience for a web application.



**DevSecOps** - an integration of security into the DevOps process that ensures that security is considered in every stage of the SDLC and not as a final product but at every point in the cycle.

### Key Principles:
1. **Security as Code**: The security practice should be automated and integrated into the development.
2. **Shift Left**: Address security concerns as early in the development cycle as possible, before it slips past.
3. **Integration**: Developers, security teams, and operations come together to assure security is not a point effort.
4. **Automation**: Most of the scans, testing, and patching are automated security checks.
5. **Monitoring**: Security continuously monitors in real-time during both development and deployment.

### Advantages:
It enables faster discovery of vulnerabilities.
Faster delivery time because of low costs due to the early identification of security bugs.
Improved inter-team collaboration and better integration through CI/CD pipelines.
Enhanced security through the monitoring and constant testing.

Common Tools are:
- **SAST/DAST**: SonarQube, Checkmarx, OWASP ZAP.
- **CI/CD Integration:** Jenkins, GitLab CI.
- **IaC Security**: Terraform, Ansible.
- **Monitoring**: Splunk, Datadog.

In summary, DevSecOps brings security in the development process continuously and automatically while facilitating fast and secure delivery of software products.


SAST (Static Application Security Testing) Tools
SAST scanning tools look through the application code, including either source code or bytecode/binary, to recognize vulnerabilities without actually having to execute an application.
Essential Characteristics of SAST :

    The technology detects potential holes in an early development stage shifting left.
The code is statistically analyzed for error-prone detection of bugs: SQL injection vulnerabilities, XSS flaw, insecure application programming interface -API.
Integrates with CI/CD pipelines and IDEs for seamless code reviews.

Examples of SAST Tools:

    SonarQube - Open-source platform for continuous inspection of code quality.
    Checkmarx - Comprehensive source code scanning.
    Fortify Static Code Analyzer (SCA) - Advanced static analysis for large applications.
    Veracode Static Analysis - Automated code reviews for secure coding.
Coverity - It detects source code critical defects.

DAST Tools (Dynamic Application Security Testing)

DAST means testing the application running under real-world attacks simulating it. The main features of DAST are:

    Finds the vulnerability in the application's run time environment.
    Focuses on the outer behavior of the web applications.
    It is ideal for determining troubles like authentication flaws and misconfigurations and at runtime vulnerabilities.
Useful during the testing and staging phases of the software development lifecycle.

Examples of DAST Tools:

    OWASP ZAP (Zed Attack Proxy) - Open-source tool for web application security testing.
    Burp Suite - Comprehensive penetration testing toolkit.
    Acunetix - Automated web vulnerability scanner.
    Netsparker - Dynamic application scanner with proof-based scanning.
AppScan-HCL Security, aims to detect vulnerabilities in a web application.


To efficiently secure web applications, follow these key steps:

1. **Secure Authentication**: Use strong passwords, MFA, and secure sessions.
2. **Data Encryption**: Use HTTPS, encrypt data at rest (AES-256), and hash passwords (bcrypt/Argon2).
3. **Input Validation**: Sanitize and validate inputs to prevent XSS and injection attacks.
4. **Access Controls**: Implement RBAC and the least privilege principle.
5. **Secure Code**: Scan code, update dependencies, and avoid hardcoding secrets.
6. **Security Headers**: Use CSP, HSTS, and X-Frame-Options.
7. **Test Regularly**: Perform penetration testing and use tools like OWASP ZAP.
8. **Monitor and Respond**: Log activity, monitor threats, and set up an incident response plan.
9. **Educate Developers**: Train on secure coding and OWASP best practices.
10. **Update and Patch**: Regularly patch systems and automate updates.
11. **Use a WAF**: Protect against malicious traffic in real-time.

Prioritize continuous monitoring and regular updates to stay secure.

![WhatsApp Image 2025-01-22 at 21 20 32](https://github.com/user-attachments/assets/b77e4c08-b379-42a9-acd5-cc4c8cf83bac)


![Screenshot 2025-01-22 at 11 00 01 PM](https://github.com/user-attachments/assets/859b2f48-9f6f-4d57-a482-79dc4104aa95)





Sources used --
*GreeksforGreeks
*Stackflow
*Reddit

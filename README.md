# InfoSec_h2

x) Read and summarize (This subtask x does not require tests with a computer. Some bullets per article is enough for your summary, feel free to write more if you like)
+ OWASP: OWASP 10 2021
   1) A05:2021-Security Misconfiguration

Security Misconfiguration is a vulnerability that occurs when security settings on systems and applications are not properly configured, allowing unauthorized access to sensitive information. The most common causes of security misconfigurations are:

   - Applications and systems often come with default configurations that are not secure.

   - Misconfigurations can occur when changes are made to the system or application without fully understanding the implications of the changes.

   - Incomplete configurations, Some systems or applications may not be fully configured, leaving certain security settings incomplete.

   - Systems and applications can become vulnerable over time if security configurations are not kept up to date.

   - Security configurations may deteriorate over time due to a lack of maintenance and regular security checks.

It is important to properly configure systems and applications to minimize the risk of security misconfigurations. The best implemention practices would be regularly checking for misconfigurations, and maintaining up-to-date security configurations.


   2) A06:2021-Vulnerable and Outdated Components
    
Vulnerable and outdated components refer to software libraries, frameworks, and other components used in the development of software applications that have known security vulnerabilities. Those components may become obsolete and no longer receive security updates, leaving the applications that use them vulnerable to attack.

This can include:

   - Libraries used in software development may have vulnerabilities that have been discovered and fixed in newer versions, but the applications using these libraries      may not have been updated to use the newer versions.

   - Frameworks used in software development may have vulnerabilities that have been discovered and fixed, but the applications using these frameworks may not have          been patched to address the vulnerabilities.

   - Deprecated components, this may become deprecated and no longer receive security updates, making them vulnerable to attack.
    
It is very important to regularly check for and update vulnerable and outdated components in software applications to minimize the risk of security vulnerabilities. This would include regularly checks for security updates, implementing a software composition analysis tool, and conducting regular security assessments.
    
    
   3) A03:2021-Injection
    
Injection is a type of security vulnerability that occurs when an attacker is able to inject malicious code into an application or system. This method allows the attacker to take control of the affected system or steal sensitive information. Some common types of injection attacks include:

   - The most common SQL Injection. An attacker injects malicious SQL code into an application that interacts with a database, allowing the attacker to manipulate the      database or steal sensitive information.

   - Next one is command Injection. When attacker injects malicious code into an application that uses system commands, allowing the attacker to execute arbitrary code      on the affected system.

   - Cross-Site Scripting (XSS) is used to injects malicious JavaScript code into a web application, allowing the attacker to steal sensitive information or perform        other malicious actions.

   - The Remote Code Injection method which is allowing the attacker to take control of the remote system.

To prevent injection attacks, it is important to validate user input and sanitize any user-supplied data before using it in an application or system. To exclude and minimize those risks we can use the proper input validation and output escaping, using parameterized queries, and regularly updating software components and libraries.
    
    
   4) Any episode from Darknet Diaries.




+ Pick a CVE, and briefly explain it & why it matters





### a) Sequel. Solve SQLZoo:
* 0 SELECT basics

![Action Matrix Model](1.JPG)

* 2 SELECT from World, from first subtask to 5 "France, Germany, Italy"

![Action Matrix Model](2.JPG)
![Action Matrix Model](3.JPG)
![Action Matrix Model](4.JPG)
![Action Matrix Model](5.JPG)
![Action Matrix Model](6.JPG)

### b) Injected. Solve WebGoat:
* A1 Injection (intro)

![Action Matrix Model](8.JPG)



### m) Voluntary bonus: Pick your tasks from SQLZoo 1, 3-9.


![Action Matrix Model](9.JPG)
![Action Matrix Model](10.JPG)
![Action Matrix Model](11.JPG)
![Action Matrix Model](12.JPG)
![Action Matrix Model](13.JPG)


### n) Voluntary difficult bonus: WebGoat: SQL Injection (advanced).

![Action Matrix Model](7.JPG)



## References: 

* https://terokarvinen.com/2023/information-security-2023/?f=moodle
* https://owasp.org/Top10/A05_2021-Security_Misconfiguration/
* https://owasp.org/Top10/A06_2021-Vulnerable_and_Outdated_Components/
* https://owasp.org/Top10/A03_2021-Injection/
* https://darknetdiaries.com/
* https://cvetrends.com/
* https://cve.mitre.org/
* https://news.ycombinator.com/

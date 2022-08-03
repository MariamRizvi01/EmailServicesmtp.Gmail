# EmailServicesmtp.Gmail
Creating a Java Program by accessing Gmail's smtp, and sending out emails using SpringBoot Frame Work.

# Java Project - JAVA Mail Sender Service using GMAIL's smtp*

**NOTE: Being that Google removed "Less App Security", it will not allow Third-Party interfaces/programs/apps to access private data because of security reasons.**

Submitted by: Mariam Rizvi

Time spent: **13-20** days spent in total

## The Use of Spring Boot / Spring Initializer

The following is **required** to improve functionality until programs runs succesfully:

* [ ] Prime reason of using the SpringBootIntializer instead of manually importing Javax.Mail API libraries and creating Maven Dependents because SpringBoot implements embedded TomCat, and SpringWorks needed for Gmail SMTP. And reduced amounts of source codes as well as runtime, therefore classes can be called properly and efficently.
* [ ] Importing Javax.Mail.JAR and Activiation.JAR interfered with memory space, and importing specific libraries could not be called. 
* [ ] Created several packages and under those packages, classes were created and a interface. Such as the CONTROLLER, SERVICE, RESOURCE, INTERFACE, and APPLICATION PROPERTIES. Each class is significant in order to specify the important features under that class for MAIN.

Challenges faces during the process of developing the interface. 

* [ ] FIRST ISSUE: On May 30th 2022, Google has blocked sign-in attempts from some "third-party" apps that do not use modern security standards. Since these apps and devices are easier to break into, blocking them helps keep your account safe. Therefore, they have removed "Less Secure App Access" application.
* [ ] SECOND ISSUE: In order to access the user's GMAIL account, without EXPLICILTY displaying the password & username in the lines of the code. Utilized the "Application.Properties", and added enviromental variables to embed and configure a PASS to execute the operating system successfully.
* [ ] THIRD ISSUE: Being that GMAIL.smtp.host has different port numbers for TLS and SSL. Ports 25 and 465 did not work. This post: 587, worked thus returning local host /8080/.

The following **optional** features are implemented:

* [ ] Used PostMan to test the program side to the GMAIL's server and receive a response.

The following **additional** features are implemented:

* [ ] Future edits coming soon.

Future additional features to come:
* [ ] Debugging or creating another FrameWork to bypass the "Internal Server Error 500". Error was called due to Third-Party Security applications removed by Google. Which causes the interface to not send the email.

For more inquires please email @miriamrizviofficial@gmail.com


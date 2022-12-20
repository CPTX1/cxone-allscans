<<<<<<< HEAD
This is a "Vulnerable" Web Application developed by Cyber Security and Privacy Foundation(www.cysecurity.org). This app is intended for the Java Programmers and other people who wish to learn about Web application vulnerabilities and write secure code.

**The full course content is now available on Github for free:**

https://github.com/CSPF-Founder/JavaSecurityCourse


**The full course on Hacking and Securing Web Java Programs is available in** 

https://www.udemy.com/hacking-securing-java-web-programming/

**Warning**: Don't run this app in Your Main Machine or in  an online server.  Install it in Vitual Machine.

 
How to Use/Setup ?
-------------

**Method 1.Super Very Easiest Method: Docker**
  The easiest way to use Java Vulnerable is using Docker which set up everything for you with 1 command line

  Steps:

     1. Install Docker: https://docs.docker.com/engine/installation/ 
     2. Install docker-compose: https://docs.docker.com/compose/install/
     3. Inside this directory, run `sudo docker-compose up` and wait untill everything is configured for you.
     4. In your Browser, go to "http://localhost:8080/JavaVulnerableLab/install.jsp
     5. Change the JDBC URL from jdbc:mysql://localhost:3306 to jdbc:mysql://mysql:3306
     6. Click the Install Button
     7. Enjoy :)


**Method 2.Very Easiest Method : VirtualBox VM**
  The second most easiest way to use Java Vulnerable is using the VirtualBox VM which has everything set up and ready to use. 
  
  Steps:
      
      1. Install the VirtualBox : https://www.virtualbox.org/wiki/Downloads
      2. Download the VM Image from here : http://sourceforge.net/projects/javavulnerablelab/files/v0.1/JavaVulnerableLab.ova/download
      3. Import the JavaVulnerable.ova into VirtualBox.
      4. Change the Network Settings to Host-Only Network 
      5. Start the Machine and Log into the Machine( Credentials; username: root password: cspf) 
      6. Start Tomcat by entering "service tomcat start" in the Terminal
      7. Start mysql by entering "service mysql start" in the Terminal
      8. Find the IP Address of Machine
      9. In your Browser, go to "http://[IP_ADDRESS_OF_VM]:8080/JavaVulnerableLab/install.jsp 
      10. Click the Install Button
      11. Enjoy :)
      
**Method 3.Easiest Method : Standalone Web Application**
  In this mehtod, you will be running an executable "JAR" file which runs the application with an embedded Apache Tomcat. 
 
    Steps:
    
        1. Install JDK
        2. Download Executable Jar from here: http://sourceforge.net/projects/javavulnerablelab/files/v0.2/JavaVulnerableLab.jar/download
        3. Double Click the JavaVulnerable.jar to run( if double click is not working, run this command "java -jar JavaVulnerable.jar" in your Terminal or CMD)
        4. In your Browser, go to "http://localhost:8080/JavaVulnerableLab/install.jsp 
        5. Click the Install Button
        
**Method 4. Using War file:**
  This is a NORMAL method to deploy the WAR file. 
  
  Steps:
  
       1. Install Apache Tomcat server
       2. Go to http://[Tomcat_INSTALLED_IP]:8080/manager/  (make sure you have modified tomcat-users.xml file of the tomcat to allow the manager).
       3. Download our WAR file from here: https://sourceforge.net/projects/javavulnerablelab/files/latest/JavaVulnerableLab.war/download
       4. Deploy the WAR in Apache Tomcat manager.
       5. Go to http://[Tomcat_INSTALLED_IP]:8080/JavaVulnerableLab/install.jsp 
       6. Click the Install Button
       

Get the VulnerableSpring Project from here:
https://github.com/CSPF-Founder/VulnerableSpring

=======
# Introduction 
TODO: Give a short introduction of your project. Let this section explain the objectives or the motivation behind this project. 

# Getting Started
TODO: Guide users through getting your code up and running on their own system. In this section you can talk about:
1.	Installation process
2.	Software dependencies
3.	Latest releases
4.	API references

# Build and Test
TODO: Describe and show how to build your code and run the tests. 

# Contribute
TODO: Explain how other users and developers can contribute to make your code better. 

If you want to learn more about creating good readme files then refer the following [guidelines](https://docs.microsoft.com/en-us/azure/devops/repos/git/create-a-readme?view=azure-devops). You can also seek inspiration from the below readme files:
- [ASP.NET Core](https://github.com/aspnet/Home)
- [Visual Studio Code](https://github.com/Microsoft/vscode)
- [Chakra Core](https://github.com/Microsoft/ChakraCore)
>>>>>>> 0aa835f61eb9bda6c12170bf87133526c0a44807

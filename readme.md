# Weekly Assignment Instructions


### Overview

This week we will be reviewing authentication and authorization methods!  We will cover various methods of authentication, the multiple ways people can "prove" who they are, and you will get some hands-on experience adding "Basic" authentication to a Spring Boot API (hint - this is a preview of one of the requirements in your group projects this week!) 

### Learning Outcomes

You will learn what authentication and authorization are.  You will also learn about the various types of authentication you can use to validate credentials and get some hands-on experience with implementing authentication at the application level!
    

### Instructions
1. **Review the following materials**:

   - [Frontegg - What is Authentication and how it works](https://frontegg.com/blog/authentication)

   This blog post provides a really in-depth view into what authentication is and the various types.  Though much of the IT world today utilizes token-based authentication (such as JSON Web Tokens (JWTs)) we will be implementing "BASIC" authentication in our hands-on assignment this week! 

   - [Keeper - types of Multifactor Authentication](https://www.keepersecurity.com/blog/2023/06/27/types-of-multi-factor-authentication-mfa/)

    In this article Keeper (a vendor of Password Management solutions) reviews the various types of multifactor authentication!

   - [Okta - Authentication vs Authorization](https://www.okta.com/identity-101/authentication-vs-authorization/)

    This is a great short article on the difference between authentication and authorization from an organization that specializes in offering related services!

   - [Bellsoft Liberica OpenJDK](https://bell-sw.com/pages/downloads/)

    You will need to install a version of the "Java Development Kit (JDK)" to run this project!  Please download and install the OpenJDK 21, open a terminal, and run "java --version" to ensure you get a response that proves you have installed a functional Java version!

   - [Spring](https://spring.io/why-spring)
  
     This page on the "https://spring.io" website explains what the Spring "framework" is and why it's so popular!  If you work for a shop that develops their own software or implements vendor software there is a really good chance you'll come across Java applications, and you'll find that many of those applications are powered by the Spring Framework!

   - [Introduction to Spring Framework](https://youtu.be/Zxwq3aW9ctU?si=ADiE2IryDSgvkTdU)

   This video provides a brief introduction into why Spring is so popular in the Java application development ecosystem!


3. **Complete the following tasks**:

   - First, install Bellsoft Libera OpenJDK Java version 21 on your host (personal) machine!

   - Next, please "Clone" (Download) this project.  Once downloaded open a terminal in the root directory of this project.  You should be able to run:

   ```Bash
    ./mvnw spring-boot:run
   ```

   This will start the "Spring" application on your local machine at port 8080.  You should be able to go to the following endpoints on your application:

    http://127.0.0.1:8080/home
    http://127.0.0.1:8080/hello

   - The thing is, we want the "/hello" endpoint to sit behind authentication!  Please follow  this tutorial [Securing a "Spring" Web application](https://spring.io/guides/gs/securing-web#scratch) to add "Basic" authentication to this web application!  While this is DEFINITELY not the "approved" method of authenticating (i.e. the user/password is in memory and directly in our source code) it will provide a basis for adding user authentication to your group projects!
  
   - Once you have added Basic authentication and validated that you need to "login" to see the "/hello" endpoint please commit your changes to your local repository and push them to a public repository in your GitHub account!  Then please submit that URL to this assignment on Brightspace!
"# Week4-Assignment" 
"# Week4-Assignment" 

Shopizer (for java 1.8 +)
-------------------
[![last_version](https://img.shields.io/badge/last_version-v2..6.0-blue.svg?style=flat)](https://github.com/shopizer-ecommerce/shopizer/tree/2..6.0)
[![Official site](https://img.shields.io/website-up-down-green-red/https/shields.io.svg?label=official%20site)](http://www.shopizer.com/)
[![Docker Pulls](https://img.shields.io/docker/pulls/shopizerecomm/shopizer.svg)](https://hub.docker.com/r/shopizerecomm/shopizer)
[![stackoverflow](https://img.shields.io/badge/shopizer-stackoverflow-orange.svg?style=flat)](http://stackoverflow.com/questions/tagged/shopizer)
-------------------

Java open source e-commerce software
- User authentication
- Product Catalogue
- Shopping cart
- Search
- Checkout
- Administration
- REST API
  ![Screenshot 2024-01-26 164433](https://github.com/the-lasya-projects/Online_Shopping_Platform/assets/142709321/482982b9-628f-454b-8e39-b9a5d5e34212)
  ![Screenshot 2024-01-26 164443](https://github.com/the-lasya-projects/Online_Shopping_Platform/assets/142709321/0bad9588-0a2b-4ba4-8356-663b578787da)



See the demo:
-------------------
http://demo.shopizer.com:8080


Get the code:
-------------------
Clone the repository:
     
	 $ git clone git://github.com/shopizer-ecommerce/shopizer.git

If this is your first time using Github, review http://help.github.com to learn the basics.

You can also download the zip file containing the code from https://github.com/shopizer-ecommerce/shopizer 

To build the application:
-------------------	
From the command line with Maven installed:

	$ cd shopizer
	$ mvn clean install
if Maven is not installed, use maven wrapper
       
	$ mvmw clean install
	

Run the application from Tomcat 
-------------------
copy sm-shop/target/ROOT.war to tomcat or any other application server deployment dir

Increase heap space to 1024 m

### Heap space configuration in Tomcat:


If you are using Tomcat, edit catalina.bat for windows users or catalina.sh for linux / Mac users

	in Windows
	set JAVA_OPTS="-Xms1024m -Xmx1024m -XX:MaxPermSize=256m" 
	
	in Linux / Mac
	export JAVA_OPTS="-Xms1024m -Xmx1024m -XX:MaxPermSize=256m" 

Run the application from Spring boot 
-------------------

       $ cd sm-shop
       $ mvn spring-boot:run
if Maven is not installed, use maven wrapper
       
	   $ mvmw spring-boot:run

Run the application from Spring boot in eclipse
-------------------

Right click on com.salesmanager.shop.application.ShopApplication

run as Java Application

### Access the application:
-------------------

Access the deployed web application at: http://localhost:8080/

Acces the admin section at: http://localhost:8080/admin

username : admin

password : password

The instructions above will let you run the application with default settings and configurations.
Please read the instructions on how to connect to MySQL, configure an email server and configure other subsystems


### Documentation:
-------------------

Documentation available from the wiki <http://shopizer-ecommerce.github.io/shopizer/#>

ChatOps <https://shopizer.slack.com>  - Join our Slack channel https://shopizer-slackin.herokuapp.com/

More information is available on shopizer web site here <http://www.shopizer.com>

### Participation:
-------------------

If you have interest in giving feedback or for participating to Shopizer project in any way
Feel to use the contact form <http://www.shopizer.com/contact.html> and share your email address
so we can send an invite to our Slack channel




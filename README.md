# Configure HTTPS/SSL in spring-boot application

After cloning this project execute below command to start spring-boot application
<p>
<code>
mvn spring-boot:run
</code>
</p>

Currently self signed certificate is created using below command:

<p>
<code>
C:\> keytool -genkey -keyalg RSA -dname "cn=Chintan Patel, ou= DevOps, o=mycompany, c=IN" -alias mycompany
-keystore src/main/resources/testkeystore -storepass changeit -validity 360 -keysize 2048

EnteEnter key password for<mycompany> (RETURN if same as keystore password):
</code>
</p>

For more information visit my blog post at wordpress:
[Configure HTTPS/SSL in Spring Boot application](http://wp.me/p7zWEq-1d)



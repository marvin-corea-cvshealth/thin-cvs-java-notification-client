# ![image](https://github.com/jmconelogin/jmconelogin/blob/main/custom_logo.png)thin-cvs-java-notification-client 
The notification health client is Java-based thin client to send prescription notification emails from CVS.

Email text:
This is a reminder from CVS Mart at Blue Ave. You have prescriptions ready for pickup. Questions? Please call us at (999) 999-9999.

## Adding cvs-notification-client to your project
### POM
    <dependency>
        <groupId>com.cvs.notification</groupId>
        <artifactId>cvs-notification-client</artifactId>
        <version>0.0.1-SNAPSHOT</version>
        <systemPath>${pom.basedir}/src/main/resources/cvs-notification-client-0.0.1-SNAPSHOT.jar</systemPath>
        <scope>system</scope>
    </dependency>
 ### Sample code
    import com.cvs.notification.NotificationClient;
    NotificationClient client = new NotificationClient();
    client.callNotification(userEmail, "Refill");
 ### Output
![image](https://user-images.githubusercontent.com/98829230/156652536-1fd7358d-1ac7-45a0-bd45-f03af0f94bfe.png)

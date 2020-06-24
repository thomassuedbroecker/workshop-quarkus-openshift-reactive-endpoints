# Exercise 1: Deploy Kafka via Script

In this short lab you'll deploy Kafka, PostgreSQL, and the Microservices of the reactive example via a script.

### Step 1: Deploy the example application

Invoke the following command:

```
$ ~/cloud-native-starter/reactive/os4-scripts/deploy-example.sh 
```

The deployment takes approximately 10 minutes shows the links to the Services and Web-App.

To launch the web application get the URLs from the last output.

![](../../images/verify-app5.png)

Open the web application in a browser. Then invoke the curl post command. The web application should show the new entry.

![](../../images/verify-app6.png)



### Step X (Optional): Verify the deploy Services and Web Application

Make sure all four pods in the 'cloud-native-starter' project are running.

![](../../images/verify-app1.png)

The previous steps have create build configs, builds and image streams.

![](../../images/verify-app2.png)

![](../../images/verify-app3.png)

![](../../images/verify-app4.png)

To launch the application get the URLs via the following command.



# Exercise 1: Deploy Kafka via Script

In this short lab you'll deploy Kafka, PostgreSQL, and the Microservices of the reactive example via a script.

### Step 1: Deploy the example application

Invoke the following command:

```
$ bash ~/cloud-native-starter/reactive/os4-scripts/deploy-example.sh 
```

The deployment takes approximately 10 minutes shows the links to the Services and Web-App.

![](../../images/setup-example-application.gif)


### Step 2: Launch the web application

To launch the web application get the URL from the last output and open the application in a browser.

![](../../images/web-app-url.png)

### Step 3: Copy the curl command

Copy the curl command to create a new article and insert it into the current terminal session.

![](../../images/create-articles-curl.png)

### Step 4: Verify the application works

Open the web application in a browser. Then invoke the curl post command. The web application should show the new entry.

![](../../images/verify-app6.png)

### Step 5 (Optional): Verify the deployed PostgreSQL

You can check the status via the OpenShift web console. On the 'Pods' page select the 'postgres' project.

![](../../images/postgres-verify.png)

### Step 6 (Optional): Verify the deployed Kafka

You can check the status via the OpenShift web console. On the 'Pods' page select the 'kafka' project.

![](../../images/kafka-deployment2.png)

### Step 7 (Optional): Verify the deployed Services and Web Application

Make sure all four pods in the 'cloud-native-starter' project are running.

![](../../images/verify-app1.png)

The previous steps have create build configs, builds and image streams.

![](../../images/verify-app2.png)

![](../../images/verify-app3.png)

![](../../images/verify-app4.png)

To launch the application get the URLs via the following command.



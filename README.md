# Getting started with Tomcat on IBM Cloud

In this getting started, we'll take you through a sample Tomcat helloWorld app.


## 1. Clone the sample app

Now you're ready to start working with the sample Tomcat app. Clone the repository and change to the directory to where the sample app is located.
```
git clone https://github.com/IBM-Cloud/get-started-tomcat
cd get-started-tomcat
```

Peruse the files in the *get-started-tomcat* directory to familiarize yourself with the contents.

## 2. Run the app locally

You must install the dependencies and build a .war file as defined in the pom.xml file to run the app.

Install the dependencies.

```
mvn clean install  
```

Copy GetStartedTomcat.war from the `target` directory into your `tomcat-install-dir` `webapps` directory.

Run the app.  
```
<tomcat-install-dir>/bin/startup.bat|.sh
```

View your app at: http://localhost:8080/GetStartedTomcat/


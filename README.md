#Java Mongo Hello Galaxy Sample Application

##Where are the important files?

###Relevant files:

####src/com/ibm/informix/java_mongo_HelloGalaxy.java

This file contains all of the sample data interacting with the database.

####manifest.yml

If deploying to bluemix, this file gives details about the application.

####build.gradle

This file gathers dependencies and will build a war file if needed to deploy to Bluemix.

##What can I do with this example?

###Option 1: Deploy to Bluemix

####Requirements:

Git - Used to download the application.

Gradle -  Used to get dependencies and build the application.

CloudFoundry CLI -  Used to push the application to Bluemix.

####Procedure:

 * Step 1: Clone repository to local machine

 * Step 2: Use gradle to build a war file.
 
 * Step 3: Update the manifest.yml to match the name, host, and domain of your Bluemix application.
 
 * Step 4: Push application to Bluemix using CloudFoundry CLI.

###Option 2: Run locally

####Requirements:

Git - Used to download the application.

Gradle -  Used to get dependencies.

####Procedure:

 * Step 1: Clone repository to local machine
 
 * Step 2: Specify the connection information

 * Step 3: Use gradle to copy runtime dependencies

 * Step 4: Deploy as a web application

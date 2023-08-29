## Deploying wiris.net on Tomcat 9: Step-by-Step Guide

Follow these steps to successfully deploy wiris.net on Tomcat 9:

### Step 1: Download the plugins.war File

Visit the [release section of the plugins repository](https://github.com/wiris/plugins/releases) and download the latest plugins.war file.

### Step 2: Place plugins.war in the Resource Folder

Create resources folder.

Locate the resources folder within your project and place the downloaded plugins.war file in this folder.

### Step 3: Start the Docker Container

Navigate to the root folder of your project using the terminal. Execute the following command to initiate the Docker container:

```
docker-compose up
```

### Step 4: Verify Deployment

Open a web browser and go to the following URL: http://localhost:8080/plugins/plugins/app/configurationjs. This will allow you to check if the deployment was successful.

By following these steps, you'll be able to deploy wiris.net on Tomcat 9 and verify its correct deployment.

Please make sure to adjust any paths or commands based on your project's specific structure and requirements.







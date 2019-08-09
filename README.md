---
page_type: sample
languages: java
products: azure
services: Appservice
platforms: java
author: yaohaizh
---

## Getting Started with Appservice - Manage Function App Logs - in Java ##


  Azure App Service basic sample for managing function apps.
   - Create a function app under the same new app service plan:
     - Deploy to app using FTP
     - stream logs synchronously for 30 seconds
     - stream logs asynchronously until 3 requests are completed
 

## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-java/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/app-service-java-manage-logs-for-function-apps.git

    cd app-service-java-manage-logs-for-function-apps

    mvn clean compile exec:java

## More information ##

[http://azure.com/java](http://azure.com/java)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
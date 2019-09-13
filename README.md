---
page_type: sample
languages:
- java
products:
- azure
description: "Azure App Service basic sample for managing web apps."
urlFragment: app-service-java-configure-deployment-sources-for-web-apps
---

# Getting Started with Appservice - Manage Web App Source Control - in Java #


  Azure App Service basic sample for managing web apps.
   - Create 6 web apps under the same new app service plan:
     - Deploy to 1 using FTP
     - Deploy to 2 using local Git repository
     - Deploy to 3 using a publicly available Git repository
     - Deploy to 4 using a GitHub repository with continuous integration
     - Deploy to 5 using Web deploy
     - Deploy to 6 using WAR deploy
     - Deploy to 7 using ZIP deploy
 

## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-java/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/app-service-java-configure-deployment-sources-for-web-apps.git

    cd app-service-java-configure-deployment-sources-for-web-apps

    mvn clean compile exec:java

## More information ##

[http://azure.com/java](http://azure.com/java)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

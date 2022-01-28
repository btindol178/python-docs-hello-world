---
page_type: sample
description: "A minimal sample app that can be used to demonstrate deploying Flask apps to Azure App Service on Linux."
languages:
- python
products:
- azure
- azure-app-service
---

# Python Flask sample for Azure App Service (Linux)

This is a minimal Flask app that can be deployed to Azure App Service on Linux.

For instructions on running and deploying the code, see [Quickstart: Create a Python app in Azure App Service on Linux](https://docs.microsoft.com/azure/app-service/quickstart-python).

## Contributing

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.


Steps to Deploy in Order!!!!!!!!!!!!!!!!!!
##########################################
##### FIRST DISCONNECT TO THE VPN ########
##########################################
- https://portal.azure.com/#home
- https://portal.azure.com/#create/hub
- Open cloud shell create free storage
- az login (then login at link with the code provided)
- go to https://github.com/btindol178/python-docs-hello-world and click code then copy url
- git clone https://github.com/btindol178/python-docs-hello-world.git
- cd python-docs-hello-world/
- az webapp up -n unizglobalznamzezforzappz ((# This is creating web app with unique global name for web app ))

- When click on link in shell remove anything after .net

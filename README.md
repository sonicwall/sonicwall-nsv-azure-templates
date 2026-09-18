# nsv-azure-templates

SonicWall NSv - Azure resource manager templates

https://www.sonicwall.com/


Deploying
=========

Marketplace deployment
--------------------------

Find the SonicWall NSv product in Azure Marketplace: https://azuremarketplace.microsoft.com/marketplace/apps?search=sonicwall

ARM template deployment
-----------------------

Press the "Deploy to Azure" button to load the ARM template into your Azure subscription. 

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fsonicwall%2Fsonicwall-nsv-azure-templates%2Fmaster%2FmainTemplate.json)


Press the "Deploy to Azure" button below to load the ARM template with custom UI into your Azure subscription.

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fsonicwall%2Fsonicwall-nsv-azure-templates%2Fmaster%2FmainTemplate.json/createUIDefinitionUri/https%3A%2F%2Fraw.githubusercontent.com%2Fsonicwall%2Fsonicwall-nsv-azure-templates%2Fmaster%2FcreateUiDefinition.json)


This button deploys the mainTemplate with the UI definition file. The UI definition file is used to create a custom deployment experience in the Azure portal. The UI definition file is not required to deploy the template.

[![Deploy to Azure](http://azuredeploy.net/deploybutton.png)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fsonicwall%2Fsonicwall-nsv-azure-templates%2Fmaster%2FmainTemplate.json/createUIDefinitionUri/https%3A%2F%2Fraw.githubusercontent.com%2Fsonicwall%2Fsonicwall-nsv-azure-templates%2Fmaster%2FcreateUiDefinition.json)


To find out more about ARM templates refer to https://docs.microsoft.com/en-us/azure/azure-resource-manager/resource-group-template-deploy#deploy-with-azure-cli

***


⚠️ Tech Preview – Azure v5 Instances
-----------------------
Support for Azure v5 VM instances is currently available as a Tech Preview.
This capability is provided for evaluation and validation purposes and has not yet reached General Availability (GA).
Customers are encouraged to deploy and validate NSv on v5 instances in non-production/test environments before considering production deployment.

**Tech Preview limitations:**
- Functionality and performance are subject to change. 
- The configuration has not yet completed full GA-level validation. 
- Customers may encounter issues that are addressed in subsequent releases.

**Target:** General Availability for Azure v5, v6, and v7 instance support is planned for Feb/Mar 2027.


# License

Copyright © 2018 SonicWall, Inc.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated files (the "Software"), to utilize the Software
without restriction, including without limitation the rights to use, copy, 
modify, merge, publish, distribute, sublicense, and/or sell copies of the 
Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included
in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.  IN NO EVENT SHALL
THE AUTHORS OR COPYRIGHT HOLDERS OR SONICWALL BE LIABLE FOR ANY CLAIM,
DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR
OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR
THE USE OR OTHER DEALINGS IN THE SOFTWARE.
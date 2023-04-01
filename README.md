# azure-function-openapi
Add Open API Support to existing Azure function V4 - developed using in process model

**nuget package** `Microsoft.Azure.WebJobs.Extensions.OpenApi `

steps
- create function app and host it on azure
- create an apim
- import function app in apim using open api 
- set the function access code in apim as inbound processing query parameter

browse the swagger on hosted function app e.g
https://[FunctionAPPName].azurewebsites.net/api/swagger.json

![](docs/2023-03-31%2010_39_46-.png)

![](docs/2023-03-31%2010_42_39-.png)

![](docs/2023-03-31%2010_55_39-functionappopenapiaj%20-%20Microsoft%20Azure.png)

References:

1. [Official Documentation](https://github.com/Azure/azure-functions-openapi-extension/blob/main/docs/enable-open-api-endpoints-in-proc.md)

2. [Enabling OpenAPI Specifications for Azure Function](https://blogs.perficient.com/2022/05/09/enabling-openapi-specifications-for-azure-function/#:~:text=In%20November%202021%2C%20Azure%20Functions%20provided%20support%20to,possible%20by%20the%20usage%20of%20NuGet%20Package%20Microsoft.Azure.WebJobs.Extensions.OpenApi.)
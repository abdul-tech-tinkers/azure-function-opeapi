# azure-function-openapi
Add Open API Support to existing Azure function V4 - developed using in process model

steps
- create function app and host it on azure
- create an apim
- import function app in apim using open api. e.g link 
- set the function access code in apim as inbound processing query parameter

browse the swagger on hosted function app e.g
https://functionappopenapiaj.azurewebsites.net/api/swagger.json

![](docs/2023-03-31%2010_39_46-.png)

![](docs/2023-03-31%2010_42_39-.png)

![](docs/2023-03-31%2010_55_39-functionappopenapiaj%20-%20Microsoft%20Azure.png)


([Reference](https://github.com/Azure/azure-functions-openapi-extension/blob/main/docs/enable-open-api-endpoints-in-proc.md))
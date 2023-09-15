# Appsync lambda 

## How to install ?
```shell
npm install
```
## How to deploy ?
Please set up appropriate permissions for your AWS account. After that, you can deploy Appsync. In the root folder, type:
```shell
npx sls deploy --stage=dev --verbose
```
to deploy on dev stage.

## How to use ?
Once the deployment is finished, you can find the GraphQL URL and API key in the output.

1.Go to appollo sandbox https://studio.apollographql.com/sandbox/explorer
Paste into url section deployed url like so  
```text
https://ns65tuqu65cf7oeidkubn5y.appsync-api.us-west-1.amazonaws.com/graphql
```
In the header section of the explorer, paste:
```text
x-api-key: da2-6xf5na2wpvhzpn2tkewebsrd5e
```

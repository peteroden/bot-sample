# Bot Sample

A sample bot using the [Microsoft Bot Framework](https://dev.botframework.com) that demonstrates one way to automate bot testing.
A clear and simple base case bot using the [Microsoft Bot Framework](https://dev.botframework.com) that demonstrates:

* One way to automate bot testing 
* How to make a bot deployable to Azure Functions, AWS Lambda (via serverless) or restify
* LUIS.ai integration

This can be useful to those looking to get started quickly with either or all of the three points above. 

To learn how to setup continuous deployment of this bot see: [Continuous deployment for Azure Functions](https://docs.microsoft.com/en-us/azure/azure-functions/functions-continuous-deployment)

To learn how to setup the necessary environment variables, see: [How to configure Azure Function app settings](https://docs.microsoft.com/en-us/azure/azure-functions/functions-how-to-use-azure-function-app-settings).  

To get the dependent botbuilder package, run npm install within site\wwwroot\[FUNCTION_DIR]
 (see above app settings documentation on how to access Kudu).

See the latest build in Travis CI from:

[![Build Status](https://travis-ci.org/vjrantal/bot-sample.svg?branch=master)](https://travis-ci.org/vjrantal/bot-sample)

More information about the automated testing aspect of this project can be found from [this blog post](http://blog.vjrantal.net/2016/10/24/continuous-delivery-of-a-node-js-bot/).

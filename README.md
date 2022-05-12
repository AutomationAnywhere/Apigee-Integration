# Automation Anywhere and Apigee Integration {#A360-Apigee-Integration .concept}

Automation Anywhere allows you to integrate Apigee with Control Room API platform. You will be able to authenticate to get access to a Control room and deploy bots using various Control Room APIs.

Apigee integration studio allows you to build integrations to connect with enterprise applications, databases and event driven systems using the features provided such as connectors, integration engine and data transformation tools. Automation Anywhere's A360 employs software bots that enable several industries to automate their repetitive business processes. Apigee will help you to create a custom integration to deploy the bots created using the A360 platform. The diagram below shows the various components of the Automation Anywhere's A360 with Apigee integration.

![](images/A360-Apigee-Integration.png)

Two integrations will be illustrated. The first integration \([Configuring the Call Integration task](configure-call-integration.md)\) is mainly used to setup all the parameters and will be passed on to the second integration \([Building the Integration](building-integration.md)\). Dividing the integration allows the second integration to get reused by calling it with different set of input parameters.

-   **[Configuring the Call Integration task](../../../topics/nirmal/A360-Apigee-Integration/configure-call-integration.md)**  
The **Call Integration** task lets you run other integrations \(sub-integrations\) from your main integration. It is built to launch the main integration by passing all the parameters.
-   **[Building the Integration](../../../topics/nirmal/A360-Apigee-Integration/building-integration.md)**  
This section provides a step by step process to build the integration. Make sure that the bot you are trying to deploy is already available in the Control room.
-   **[Getting Bot Input Parameters](../../../topics/nirmal/A360-Apigee-Integration/getting-bot-input-parameters.md)**  
This section provides you with the details on how to get the input parameters for Automation Anywhere bot that are mandatory to launch the Integration \([Apigee integration](configure-call-integration.md)\).

**Parent topic:**[Nirmal's QA Map](../../../topics/poc/qa-nirmal.md)


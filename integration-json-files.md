# Prebuilt integrations

The Automation 360 and Apigee integration has two prebuilt Apigee integrations in the form of JSON file models, the `TriggerA360Bot.json` file and the `LaunchA360Bot.json` file. Download these two integration files, upload them as new integrations in your Apigee instance, and start calling Automation 360 bots. Download the `TriggerA360Bot.json` and `LaunchA360Bot.json` files from the following location: [https://github.com/AutomationAnywhere/Apigee-Integration/tree/main/apigee-integrations](https://github.com/AutomationAnywhere/Apigee-Integration/tree/main/apigee-integrations)

**Note:** To understand how these integrations were built, see [Creating the main integration \(TriggerA360Bot.json\)](creating-main-integration.md) and [Creating a subintegration \(LaunchA360Bot.json\)](creating-sub-integration.md).

Perform the following steps to use JSONs to create the integration.

1.  Go to [Apigee UI](https://apigee.google.com/landing) and sign in.

2.  Select your organization using the drop-down menu in the top-left corner of the UI.

3.  Click **Develop** \> **Integrations**.

4.  Click **CREATE NEW**.

5.  Provide the following information:

    -   **Integration name**: Provide a name for the integration, for example, *CallSAPbot*.
    -   *\(Optional\)***Description**: Provide a description, e.g. Deploys an A360 bot.
    -   **Region**: Select a region from the list, for example, US.
6.  Click **Upload/download menu** and then select **Upload integration**.

7.  In the file browser dialog box, select the `TriggerA360Bot.json` file that you want to upload, and then click **Open**.

    Apigee creates a new version of the integration by using the uploaded file. You can view integration with all the setup information as described in [Creating the main integration \(TriggerA360Bot.json\)](creating-main-integration.md).

8.  To create another integration, click **Develop** \> **Integrations**.

9.  Click **CREATE NEW**.

10. Provide the following information:

    -   **Integration name**: Provide a name for the integration, for example, *launch-integration*.
    -   *\(Optional\)***Description**: Provide a description, for example, "Launch an Automation 360 bot."
    -   **Region**: Select a region from the list, for example, US.
11. Click **Upload/download menu** and then select **Upload integration**.

12. In the file browser dialog box, select the `LaunchA360Bot.json` file that you want to upload, and then click **Open**.

    Apigee creates a new version of the integration by using the uploaded file. You can view the integration with all the setup information as described in [Creating a subintegration \(LaunchA360Bot.json\)](creating-sub-integration.md).


**Parent topic:**[Automation Anywhere and Apigee Integration](../A360-Apigee-Integration/a360-apigee-integration.md)


# Creating the main integration \(`TriggerA360Bot.json`\)

The main integration task calls the subintegration by using the trigger ID.

This task uses the trigger ID API as a handle to identify the integrations to run. For example, if you specify the trigger ID API as `api_trigger/launchbot`, the task runs all the subintegrations that have the `api_trigger/lauchbot` trigger ID. After running a subintegration, you can also read the response of the subintegration in your main integration. Perform the following steps to create a main integration:

1.  Go to [Apigee UI](https://apigee.google.com/landing) and sign in.
2.  Select your organization using the drop-down menu in the top-left corner of the UI.
3.  To view a list of available integrations, click **Develop** \> **Integrations**.
4.  Click **CREATE NEW**.
5.  Provide the following information:
    -   **Integration name**: Provide a name for the integration from [Creating a subintegration \(LaunchA360Bot.json\)](creating-sub-integration.md).
    -   *\(Optional\)***Description**: Provide a description, for example, "Deploys an Automation 360 bot.
    -   **Region**: Select a region from the list, for example, US.
6.  To display a list of available tasks, select **Add a task/trigger** \> **Tasks**.
7.  Drag the **Call Integration** element to the integration designer.
8.  Click the **Call Integration** task element on the designer to view the **Call Integration** task configuration pane.

    ![](images/Call-Integration.png)

9.  Configure the remaining fields and define the variables \(string datatype\) for the integration. For more information about getting all the input parameters, see [Getting bot input parameters](getting-bot-input-parameters.md).
    -   *input-ControlRoomUrl*
    -   *input-Username*
    -   *input-ApiKey*
    -   *input-BotId*
    -   *input-RunAsUserId*
    -   *input-PoolId*
    -   *input-BotInputVariables*

        This task is useful when you have a dependency on another integration and want to run it from your main integration. The task runs the subintegration either synchronously or asynchronously.


**Parent topic:**[Automation Anywhere and Apigee Integration](../README)


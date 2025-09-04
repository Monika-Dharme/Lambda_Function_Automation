# Lambda_Function_Automation

Create Lambda functions that stop and start your instances
Complete the following steps:

Open the Lambda console, and then choose Create function.

Choose Author from scratch.

Under Basic information, enter the following information:
For Function name, enter a name that describes the function, such as StopEC2Instances or StartEC2Instances.
For Runtime, choose Python 3.9.
Under Permissions, expand Change default execution role.
Under Execution role, choose Use an existing role.
Under Existing role, choose the IAM role.

Choose Create function.

Choose the Code tab.
====================================================================================================================================================================================================
Choose Deploy.

On the Configuration tab, choose General configuration, and then choose Edit.

Set Timeout to 10 seconds, and then choose Save.

Test your Lambda functions
Complete the following steps:

Open the Lambda console, and then choose Functions.
Choose one of the functions.
Choose the Code tab.
In the Code source section, choose Test.
In the Configure test event dialog box, choose Create new test event.
Enter an event name, and then choose Create.
Note: Don't change the JSON code for the test event.
Choose Test to run the function.
Repeat steps 1-7 for the other function.

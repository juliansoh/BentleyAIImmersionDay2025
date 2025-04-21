([__Return to lab__](/README.md#lab-manual))
# Answer Key

## Task 6: Add an action (email action) to the agent

Edit the agent and select Add Action.

![Add Action](/images/AddAction.png)

In the search box, type "Outlook" then scroll down to locate the "Send an Email (V2)" action ite.

![Select POutlook Send an Email V2](/images/Outlook-SendAnEmailV2.png)

For this Action Item's Details:
- The Action name and Display names are mandatory and in this example, we just accept the default, but you can choose a more descriptive Action name and Display name.
- Note that the description is for the agent to know WHEN to use this action. So this is important because it serves as a trigger to fire this action item. Type "When requested to send an email from user prompt".
- Uncheck the "Ask the user before running this action" because we want the action to be automatic.
- Set End user authentication to "User authentication"
- Usage Description is optional but type "When asked to email something, this action will be triggered to send an email to a hard-coded email address"

![Details - Outlook Send an Email V2](/images/DetailsOutlookSendEmail.png)

For this Action Item's Inputs:
- Hardcode the recipient by setting the To field to "Set as a value" and type in an email address to receive emails.
- For Subject, also hardcode a value, e.g. "Message from Bentley Personal Assistant"
- For Body, set it to Dynamically fill with best option, which as you will note, is the User's entire response.

![Inputs - Outlook Send an Email V2](/images/InputsOutlookSendEmail.png)

For this Action Item's Outputs:
- Choose to send a message immediately after running this action
- Select "You create a message" for the question "How do you want to display information to the user?"

![Message to send to user](/images/OutputsOutlookSendEmail.png)

- Type a message to notify the user that this action is executed and append the information that it sent by using the {x} variable insertion function and selecting Input.Body as the variable.

![Input Body Variable](/images/InputBodyVariable.png)

([__Return to lab__](/README.md#lab-manual))




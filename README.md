---
page_type: sample
products:
- Power Apps
- Power Automate
- SharePoint
description: Power Apps solution that provides a simple workflow where staff can check-in with a photo, location, and other details directly from Microsoft Teams
urlFragment: microsoft-teams-apps-staffcheckins
---

# Staff Check-ins App Template

| [Documentation](https://github.com/OfficeDev/microsoft-teams-apps-staffcheckins/wiki/Home) | [Deployment guide](https://github.com/OfficeDev/microsoft-teams-apps-staffcheckins/wiki/Deployment-Guide) | [Architecture](https://github.com/OfficeDev/microsoft-teams-apps-staffcheckins/wiki/Solution-Overview) |
| ---- | ---- | ---- |

First-line staff in organizations typically need to communicate and check-in with their teams periodically with time-critical updates. Whether you run a construction business, landscaping, cleaning company, a delivery service, or any other business with field personnel, you need to provide your staff with an easy way to check-in with their latest status on their work. The Staff Check-ins is a Power App that provides a simple workflow where staff can check-in with a photo, location, and other details directly from Microsoft Teams.

With the app, managers or supervisors can get task updates or check-ins from employees on a schedule or an ad-hoc basis. The staff check-in can include real-time location, photos, and notes.

## Key features
 -  Managers/Supervisors can set up a one- time or recurring occurrence of a check-in request
 -  Access all the information about the team in one place and track progress - validate locations and photos to ensure that your employees are pushing accurate data
 -  Automate operations workflow by triggering reminder notifications for end-users on Microsoft Teams

Here are some of the workflows in action:

1) A manager creates a check-in request by specifying the check-in frequency and the team name through the app

![Create checkin](https://github.com/OfficeDev/microsoft-teams-apps-staffcheckins/wiki/Images/Admin_CreateCheckin.png)

2) All the team members are notified of the check-in request through a notification delivered via Power Automate in the team's General channel

![Enduser notification](https://github.com/OfficeDev/microsoft-teams-apps-staffcheckins/wiki/Images/Enduser_notification.png)

3) End users can quickly navigate to the app to provide the check-in details

![Enduser Check-in](https://github.com/OfficeDev/microsoft-teams-apps-staffcheckins/wiki/Images/Enduser_Checkin.png)

4) Managers can view summarized check-in status of team members and view details if required

![Summarized Admin reports screen](https://github.com/OfficeDev/microsoft-teams-apps-staffcheckins/wiki/Images/Admin_ReportsScreen.png)

## Legal notice

This app template is provided under the [MIT License](https://github.com/OfficeDev/microsoft-teams-apps-staffcheckins/blob/master/LICENSE) terms.  In addition to these terms, by using this app template you agree to the following:

-	You are responsible for complying with all applicable privacy and security regulations related to use, collection and handling of any personal data by your app.  This includes complying with all internal privacy and security policies of your organization if your app is developed to be sideloaded internally within your organization.

-	Where applicable, you may be responsible for data related incidents or data subject requests for data collect through your app.

-	Any trademarks or registered trademarks of Microsoft in the United States and/or other countries and logos included in this repository are the property of Microsoft, and the license for this project does not grant you rights to use any Microsoft names, logos or trademarks outside of this repository.  Microsoft’s general trademark guidelines can be found [here](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general.aspx).

-	Use of this template does not guarantee acceptance of your app to the Teams app store.  To make this app available in the Teams app store, you will have to comply with the [submission and validation process](https://docs.microsoft.com/en-us/microsoftteams/platform/concepts/deploy-and-publish/appsource/publish), and all associated requirements such as including your own privacy statement and terms of use for your app.


## Getting started

Begin with the [Solution overview](https://github.com/OfficeDev/microsoft-teams-apps-staffcheckins/wiki/Solution-overview) to read about what the app does and how it works.

When you're ready to try out Staff Check-ins app, or to use it in your own organization, follow the steps in the [Deployment guide](https://github.com/OfficeDev/microsoft-teams-apps-staffcheckins/wiki/Deployment-guide).

#### Known issue:
The app is currently not supported on mobile devices. We are actively working on fixing the issue and will update the repo as soon as it is available

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

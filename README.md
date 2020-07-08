---
page_type: sample
languages:
- csharp
products:
- office-teams
description: ScrumBot for Teams helps you get status updates from your team in channel-level scope
urlFragment: scrumbot-for-teams
---

# ScrumBot for Teams

| [Documentation](https://github.com/OfficeDev/microsoft-teams-apps-scrumsforchannels/wiki/Home) | [Deployment guide](https://github.com/OfficeDev/microsoft-teams-apps-scrumsforchannels/wiki/Deployment-Guide) | [Architecture](https://github.com/OfficeDev/microsoft-teams-apps-scrumsforchannels/wiki/Solution-Overview) |
| ---- | ---- | ---- |

ScrumBot for Teams is a scrum assistant app that enables users to schedule, configure and conduct daily scrum sessions within Microsoft Teams.

The app is installed at the team level. All members added to a scrum team can participate in scrum events.

The app runs on a fixed daily schedule enabling members to participate remotely including accommodation for various time zones.

### With the ScrumBot app in Microsoft Teams, users can:
* Run daily scrum events in a target channel
* Schedule a scrum at a specified time based on a time zone
* Select the team members who will be part of the scrum
* Configure multiple scrums to run in the same and/or different channels
* Export scrum details for the past 30 days in a flat file (CSV)

### Scrum Workflow:
1. The app will automatically start the scrum at the specified time
2. An adaptive card will appear with options to share status updates, view details entered by other scrum team members, and end the scrum.
_The card displays the status of the scrum (either `active` or `closed`), the number of participants who have contributed to the scrum or have marked their status as blocked
3. Users have the ability to share their daily scrum updates, view details submitted by other team members and end the scrum

This application is a fork of the Microsoft Office Developer open source developer tools suite on GitHub and is derived from the Scrums for Channels App Template

[View Source Repo on GitHub](https://github.com/OfficeDev/microsoft-teams-apps-scrumsforchannels)

[App Templates for Microsoft Teams](https://docs.microsoft.com/en-us/microsoftteams/platform/samples/app-templates#scrums-for-channels-)

[Office Developer Organization on GitHub](https://github.com/OfficeDev)

Here are some screenshots of a user interacting with Scrums for Channels :

**Configure scrums**

![Scrums for Channels settings task module screen](https://github.com/OfficeDev/microsoft-teams-apps-scrumsforchannels/wiki/Images/SettingsScreen.png)

**Provide your updates when a scrum is active**

![Scrum status screen adaptive card with @mentions](https://github.com/OfficeDev/microsoft-teams-apps-scrumsforchannels/wiki/Images/ScrumStatus.png)


**View details updated by you and others**

![Scrum details task module screen](https://github.com/OfficeDev/microsoft-teams-apps-scrumsforchannels/wiki/Images/ScrumDetails.png)

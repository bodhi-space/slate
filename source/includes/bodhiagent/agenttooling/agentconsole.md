##Agent Console


The Agent Console is the application that users can use to manage their Agent's functionality and settings. The following sections describe how to use the Agent Console.

### Getting Started
The Agent must be running for you to access the Agent Console. You can access the Agent Console by going to [http://localhost:4444](http://localhost:4444) in your browser. If you installed the Agent for the first time, the console will automatically start if you selected the "Start Console" option during the installation.

_Note: Agent Console works best in Google Chrome or Mozilla Firefox._

### Registering Your Agent

Upon entering the console for the first time, you should see a registration token pop up. This six-digit registration code needs to be entered into your Bodhi Mobile App to connect your Agent to your Bodhi Mobile App and to the Bodhi Cloud. Once you've successfully entered the token into the Bodhi Mobile App, the window will display a "SUCCESS" message and close. 

__Important__: If the window pops up and you don't see a token, wait 10 seconds and refresh your browser. If the window doesn't pop up, click on the Registration Code link (see circle #1)in the left navigation bar to open the window.

![Registering Your Agent](/images/agent-console-registrationcode.png?raw=true"Registering Your Agent")

_The registration code should be entered in your Bodhi Mobile App._

### Dashboard
The Dashboard displays Agent software updates, your installed Agent Apps, and Customer Support information. 

Note that clicking the three lines next to the Bodhi Agent icon (see circle #1) will enable you to minimize or expand the navigation bar.

In the top right corner, you can see the Agent's connection status to the Internet (either Online or Offline, see circle #2).

![dashboard](/images/agent-console-dashboard.png?raw=true"")
_Screenshot: Agent Console Dashboard Page_

### Integration Apps

On the Integration Apps page, you can view and install Agent Apps that are available in the Bodhi App Store. You can install apps with one click by clicking the "Install Now" button. Upon clicking it, the app will start installing. When it has finished installing, you will see a green "Installed" button.

_Note: If you receive an red error message, then the App could not be found. Make sure you are connected to the internet and if you continue to have errors, contact Customer Support._

![intregrationapps](/images/agent-console-integrationapps.png?raw=true"")
_Screenshot: Agent Console Integration Apps Page_

### Settings

On the Settings page, you can change settings that will determine how your Agent operates.

Setting | Description | 
------| --------- 
Agent Name | Changes the Agent's name 
Role | Determines the package bundles that the Agent will install
Timezone | Sets the timezone
Currency | Sets the currency for your Store

![agentsettings](/images/agent-console-agentsettings.png?raw=true"")
_Screenshot: Agent Console Settings Page_

### Connection

The Connection page displays important information about the Agent's connection details. The Connection panel displays connection status information for the Agent and the right-hand panel lists the connection protocols available to the Agent.

Setting | Description | 
------| --------- 
Status | Displays the Agent's connection to the Internet (Online/Offline)
Base | Lists the full URI path to the Bodhi Cloud
Endpoint URL | Lists the Endpoint URL that the Agent is connected to
Online Since | Lists the date & time since the Agent has been running
Interruptions | Lists the number of times the Agent had interrupted connections to the Internet

![connection](/images/agent-console-connection.png?raw=true"")
_Screenshot: Agent Console Connection Page_


### About

The About page displays information about your Agent's status. The Bodhi Agent panel lists information about your Agent's identity and structure, and the right-hand panel lists the plug-ins that are available to your Agent.

Property | Description
------| --------- 
Status | Displays the Agent's connection to the Internet (Online/Offline)
Name | Your Agent's display name
Version | The version number of the Agent
Agent Directory | Lists the directory path where the Agent is installed 
Namespace | Your identifying space in the HS Bodhi Cloud
Agent ID | The unique identifier for the Agent
Authorization | Displays whether your Agent is authorized to connect to Bodhi Cloud _(checkmark means authorized)_
Assigned | Displays whether your Agent has been assigned a Store in the Bodhi Cloud _(checkmark means assigned)_
Extensions| Lists the extensions available to the Agent (see [Extensions](/includes/bodhiagent/Howto/extensions.md))
Services| Lists the services implemented within the Agent
Handlers| Lists the event handlers implemented in the Agent
Dependencies| Lists the NPM packages that the Agent is dependent upon

![about](/images/agent-console-about.png?raw=true"") 
_Screenshot: Agent Console About Page_

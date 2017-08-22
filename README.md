# Nameless-VotingPlugin
A VotingPlugin module for the NamelessMC website software. Displays a list of the top voters from your server as well as a list of available voting sites (configurable through the AdminCP).

## Requirements:
- NamelessMC version 2 (from commit [c4ff769](https://github.com/NamelessMC/Nameless/commit/c4ff769c9d9bdadfa1db810ef69ae55ad7a18ad9) onwards)
- [VotingPlugin](https://www.spigotmc.org/resources/votingplugin.15358/) plugin for Spigot, configured to use a MySQL database

## Installation:
- Upload the contents of the **upload** directory straight into your NamelessMC installation's directory
- Activate the module in the AdminCP -> Modules tab
- Insert your VotingPlugin database details into the file **modules/VotingPlugin/config.php**
- Set up some vote sites in the AdminCP -> Vote tab

## Notes:
- Not compatible with other NamelessMC vote modules
- If you are using a custom template, make sure you add the template file (in the **custom/templates/Default** directory) to your custom template!

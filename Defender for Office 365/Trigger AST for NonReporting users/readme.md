# Trigger Attack Simulation for non-reporting users

This playbook will execute using an incident based trigger and determine which mailboxes received malicious phishing emails, and calculate which users failed to perform a user submission (Report Message as Phish) to the SOC. It will trigger an Attack Simulator 'How-To Guide' simulation to educate these end-users on the correct response when receiving a Phish email in an inbox.


[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https://raw.githubusercontent.com/jonade/SentinelRunbooks/refs/heads/main/Defender%20for%20Office%20365/Trigger%20AST%20for%20NonReporting%20users/azuredeploy.json)
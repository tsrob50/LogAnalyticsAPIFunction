# LogAnalyticsAPIFunction
Writes Hashtable data to a Log Analytics workspace 

The goal was to create a universal way to write any data to log analytics.  I did this by creating a function that takes the date, the log Type and a hashtable of key and data pairs and writes it to a Log Analytics workspace. 

The function can be added to a script and used to send data directly to Log Analytics.  I use it in a Module added to Azure Automation.  From there I can write data to Log Analytics from any Azure Automation Runbooks.  Once in Log Analytics, I can trigger alerts or tie into Logic Apps to kick off other Run Books, alerts or webhooks to other systems.


More Information can be found here:

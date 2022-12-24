# APT-Logger
Powershell APT logging 

Determine the specific indicators of exfiltration that you want to monitor. This might include specific network traffic patterns, files being transferred, or other activity that is indicative of an APT attempting to exfiltrate data.

Use the appropriate PowerShell cmdlets to monitor for these indicators. For example, you might use the Get-NetFlow cmdlet to monitor network traffic, or the Get-ChildItem cmdlet to monitor for changes to specific files or directories.

Use the Write-Output or Write-EventLog cmdlets to log any detected exfiltration activity. You may want to include details such as the source and destination IP addresses, the type of data being exfiltrated, and any other relevant information.

Schedule the script to run on a regular basis, either using the Task Scheduler or by adding it to a startup script. This will ensure that the script is constantly monitoring for exfiltration activity.

This script will monitor for the specified indicators of exfiltration, and log any detected activity to the Windows event log with a source of "APT Exfiltration Detection" and an event ID of 1. 
## **Anyone can customize the script to include additional indicators and log more detailed information as needed**

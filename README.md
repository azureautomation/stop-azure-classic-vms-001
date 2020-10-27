Stop Azure Classic VMs
======================

            
Description

This Graphical PowerShell Workflow runbook gets all of your Azure VMs or just the VMs in a service and then stops the ones that are started.  You can set this on a schedule to stop the VMs when you want.  Use in conjunction
 with StartAzureClassicVM runbook to start and stop VMs as you need them.


You can import and use this runbook in the Azure Portal.

Required

1. An Automation variable asset called AzureSubscriptionId that contains the GUID for this Azure subscription.  To use an asset with a different name you can pass the asset name as a runbook input parameter or change the
 default value for the input parameter.


2. An Automation credential asset called AzureCredential that contains the Azure AD user credential with authorization for this subscription. To use an asset with a different name you can pass the asset name as a runbook input
 parameter or change the default value for the input parameter.

Optional

A ServiceName input parameter value that allows scoping the VMs to a particular service.

Author

System Center Automation Team 

Last Edit

August 26, 2015


 


![Image](https://github.com/azureautomation/stop-azure-classic-vms/raw/master/stopazureclassicvm-screenshot.png)


 

 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.

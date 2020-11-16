# WVD QuickStart

Deploy Azure resources needed to configure an Azure DevOps pipeline.


<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fasptechcloud%2Fwvdquickstart%2Fmaster%2Fdeploy.json" target="_blank">
    <img src="https://aka.ms/deploytoazurebutton"/>
</a><br>


Once the deployment completes, please navigate to https://dev.azure.com, where you will find the WVD QuickStart project. Navigate to the "pipelines" section - Here you'll find a running pipeline that deploys a WVD environment (VMs, host pool, desktop app group, FSLogix configuration) for you. Upon completion of this pipeline, which will take about 15 minutes, the WVD environment is ready for use.

The QuickStart creates a test user for you to try out the environment. Navigate to https://rdweb.wvd.microsoft.com/arm/webclient/index.html and login with the following test user credentials:

Username: WVDTestUser001@{your-domain}.com <br>
Password: Taken from DevOps organization in the following way: If organization is called "WVDQuickStartOrg120011Z", your password will be "Org120011Z!" (case sensitive, and don't forget the exclamation point at the end) 
(Disclaimer: You should change this password at your earliest convenience.)

See separate troubleshooting guidelines




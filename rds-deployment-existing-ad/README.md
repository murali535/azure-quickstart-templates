# Create Remote Desktop Sesson Collection deployment

<IMG SRC="https://azbotstorage.blob.core.windows.net/badges/rds-deployment-existing-ad/PublicLastTestDate.svg" />&nbsp;
<IMG SRC="https://azbotstorage.blob.core.windows.net/badges/rds-deployment-existing-ad/PublicDeployment.svg" />&nbsp;

<IMG SRC="https://azbotstorage.blob.core.windows.net/badges/rds-deployment-existing-ad/FairfaxLastTestDate.svg" />&nbsp;
<IMG SRC="https://azbotstorage.blob.core.windows.net/badges/rds-deployment-existing-ad/FairfaxDeployment.svg" />&nbsp;

<IMG SRC="https://azbotstorage.blob.core.windows.net/badges/rds-deployment-existing-ad/BestPracticeResult.svg" />&nbsp;
<IMG SRC="https://azbotstorage.blob.core.windows.net/badges/rds-deployment-existing-ad/CredScanResult.svg" />&nbsp;

This template deploys the following resources:

<ul><li>RD Gateway/RD Web Access vm</li><li>RD Connection Broker/RD Licensing Server vm</li><li>A number of RD Session hosts (number defined by 'numberOfRdshInstances' parameter)</li></ul>

The template will use existing DC, join all vms to the domain and configure RDS roles in the deployment.

Click the button below to deploy

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2Frds-deployment-existing-ad%2Fazuredeploy.json" target="_blank">
    <img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2Frds-deployment-existing-ad%2Fazuredeploy.json" target="_blank">
    <img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/visualizebutton.png"/>
</a>

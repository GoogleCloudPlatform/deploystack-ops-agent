# Deploy Stack - Ops Agent 

This stack creates a Compute Engine Instance and installs the Ops Agent on it
for exploring logging and monitoring with a ready made solution. 

![opsagent architecture](architecture.png)

## Install
You can install this application using the `Open in Google Cloud Shell` button 
below. 

<a href="https://ssh.cloud.google.com/cloudshell/editor?cloudshell_git_repo=https%3A%2F%2Fgithub.com%2FGoogleCloudPlatform%2Fdeploystack-ops-agent&cloudshell_print=install.txt&shellonly=true">
        <img alt="Open in Cloud Shell" src="https://gstatic.com/cloudssh/images/open-btn.svg"></a>

Once this opens up, you can install by: 
1. Typing `./deploystack install`

## Cleanup 
To remove all billing components from the project
1. Typing `./deploystack uninstall`



This is not an official Google product.

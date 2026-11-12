# Notes made during project implementation
**During every tutorial project, I make notes on what I had to do to achieve the goal. These notes are stored here.**

1) This tutorial seems tiny, but, as with other older guides, there are complications. The starter project experience (as noted in the README) has been removed; I had to do the base project myself. The .NET code I used came from a related tutorial, https://github.com/DevCloudNinjas/DevOps-Projects/tree/master/project-07-azure-devops-aks-terraform/labs/3-Deploy-App-to-ACR.
2) The code had to be modernized as well: I moved it to .NET 10 from 3.1 and changed some calls.
3) I had to write a deployment pipeline manually as well. It is included under the name azure-pipelines.yml.
4) I used a native Azure storage to house the repository; once the tutorial was finished, I changed the upstream and posted this code on GitHub. 
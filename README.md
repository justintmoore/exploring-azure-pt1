# Exploring Azure

 ### [YouTube Demonstration](https://youtu.be/AYW6kEUMDEI)

## Description
This project provides a beginner-friendly walkthrough for setting up and managing resources within Microsoft Azure. It guides users through creating an Azure account, navigating the Azure portal, and managing resources with a focus on storage and cost management. Before beginning we will run through some basic concepts. 

The cloud is just a collection of remote servers located in a data center, spread throughout the world. These servers allow you to use resources in terms of storage, memory, computing power, in order for you to store or process your data without needing physical hardware. There are many cloud providers with notable ones being Google Cloud Provider, Azure, Amazon Web Services, Oracle Cloud, etc. <b> This project will utilize Microsoft Azure</b>.


Preface  
- First create an account with Azure. If this is your first time, you can create a free account and receive $200 in free credits. https://azure.microsoft.com/en-us/free/
  
- Log into Azure Portal https://portal.azure.com
  
- Whenever you create an Azure account, you are automatically  given a <b>Tenant</b> which represents your organization. It servers as like a Global Administrator account for your organization.  
 
- Within your Tenant, we will create a <b>Subscription</b>  which will allow us to segragrate costs and resources, such as departments within an organization. Each payment will indicate a seperate subcription. For this project we will only utilizing 1 subscription.  
  <img src="https://github.com/user-attachments/assets/62f7eb42-8e4d-4ee9-b087-f6160146584a" height="70%" width="70%" alt="Tenant.Subscription"/>

- Within your Subscriptions are <b>Resource Groups</b> that act as logical containers that help organize, manage, and control resources as a collective unit, much like folders organize files. For example things such as VMs, databases, storage accounts, etc.)  
  <img src="https://github.com/user-attachments/assets/b24167a1-a3a1-43db-921e-115e7f18673b" height="70%" width="70%" alt="ResourceGroups"/>
 
- Your Resource Groups are where your resources go, in this case we will be using the <b>Azure Storage Account</b> service. This is just a storage that can hold various types of data.  
<img src="https://github.com/user-attachments/assets/970f93f2-69e5-4c6f-b48b-c777dc016f6a" height="70%" width="70%" alt="StorageGroup"/>

 
## Tools, Utilities, Services Used
- Microsoft Azure


## Environments Used 
- Windows 10


## Program walk-through
### Part 1
- Create an Account
- While on Azure homepage, you will see Azure Services at the top of the window. There you will find "Resource Groups". If you don't see it, you can type in "Resource Groups" into the search bar.
  <img src="https://github.com/user-attachments/assets/faa7da2c-02d3-463e-bc77-cb7d4b41a0df" height="70%" width="70%" alt="home"/>
  
- Now click "Create". Choose your Resource Group name, and choose a "region", which is where the metadata or resource details of your resource group is located.  
  <img src="https://github.com/user-attachments/assets/bffb8cbc-1b10-4e49-a7ac-ee817365efc7" height="70%" width="70%" alt="rg1"/>  
  
- You can add tags to logically organize your resource groups. They consist of a key-value pair, but for now move on. Review the details of your resource group, and click "Review and Create".

- After resource group is deployed, we will create a Storage Account within the resource group.

- In the search bar above, type "storage account", after select "Create".
  <img src="https://github.com/user-attachments/assets/e74da62c-bb91-4295-9189-4b6cf378cf87" height="70%" width="70%" alt="rg1"/>

- You must declare which resource group you want to have this storage account, name your storage account (must be globally unique), change "Redundancy" to locally redudant storage (LRS). Now click "Create". 
  <img src="https://github.com/user-attachments/assets/7d1e045c-a4ab-40b2-b5fe-e9a1c6876b90" height="70%" width="70%" alt="rg1"/>

- Check to ensure that you have your resource group and storage account by navigating to your resource group, clicking it, and seeing whether or not your storage account is in there.
  <img src="https://github.com/user-attachments/assets/383537df-eb7b-49c2-a676-cd5e2610d659" height="70%" width="70%" alt="checkstorage"/>

- Now for part one we will create a text file, save it to our desktop, then upload it into the storage account.

- Go to your "storage account", on the side there should be a drop down that reads "data storage". Click that and underneath choose "container".  
  <img src="https://github.com/user-attachments/assets/f99f54a2-db30-44b0-8dad-4a83d57dc71b" height="70%" width="70%" alt="container"/>

- Click "+ Container" at the top, and name your container. This will serve almost like a folder. Now click "Create".
  <img src="https://github.com/user-attachments/assets/a5af094f-aaad-4e99-b77b-a457eaabcb24" height="70%" width="70%" alt="createcontainer"/>

- Choose your storage container, and now upload the text file we created earlier.
  <img src="https://github.com/user-attachments/assets/969a99cd-9b9f-4796-a503-c018f07a5ad3" height="70%" width="70%" alt="upload"/>

- Once uploaded we can view the text file, edit it, save it, then download it so we can save it locally on our desktop. Open up the file on your desktop to see the changes.  
  <img src="https://github.com/user-attachments/assets/d8165b48-faae-4b6e-9af9-bc51181df4c3" height="70%" width="70%" alt="editdownload"/>  

- That ends this portion of the project. You can delete each resource individually, or you can delete the resource group entirely to get rid of everything within the resource group.
- To do this go to your Resource Group page, and click "delete resource group". This will prompt you to enter the resource groups name, and click "delete".
 <img src="https://github.com/user-attachments/assets/b26282f0-75cf-4b44-ba43-6c9401a9d55c" height="70%" width="70%" alt="delete"/>
 <img src="https://github.com/user-attachments/assets/799c9a8d-fd0d-4073-9618-5f3c1e0a544a" height="70%" width="70%" alt="delete"/>
 


### Part 2

<!--
<p align="center">
Launch the utility: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>


 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>

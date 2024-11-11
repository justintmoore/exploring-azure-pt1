# Exploring Azure

 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)

## Description
This project provides a beginner-friendly walkthrough for setting up and managing resources within Microsoft Azure. It guides users through creating an Azure account, navigating the Azure portal, and managing resources with a focus on storage and cost management. Before beginning we will run through some basic concepts. 

The cloud is just a collection of remote servers located in a data center, spread throughout the world. These servers allow you to use resources in terms of storage, memory, computing power, in order for you to store or process your data without needing physical hardware. There are many cloud providers with notable ones being Google Cloud Provider, Azure, Amazon Web Services, Oracle Cloud, etc. <b> This project will utilize Microsoft Azure</b>.

Preface  
- First create an account with Azure. If this is your first time, you can create a free account and receive $200 in free credits. https://azure.microsoft.com/en-us/free/
  
- Log into Azure Portal https://portal.azure.com
  
- Whenever you create an Azure account, you are automatically  given a <b>Tenant</b> which represents your organization. It servers as like a Global Administrator account for your organization.
 
- Within your Tenant, we will create a <b>Subscription</b>  which will allow us to segragrate costs and resources, such as departments within an organization. Each payment will indicate a seperate subcription. For this project we will only utilizing 1 subscription
  <img src="https://github.com/user-attachments/assets/62f7eb42-8e4d-4ee9-b087-f6160146584a" height="70%" width="70%" alt="Tenant.Subscription"/>

- Within your Subscriptions are <b>Resource Groups</b> that act as logical containers that help organize, manage, and control resources as a collective unit, much like folders organize files. For example things such as VMs, databases, storage accounts, etc.)
  <img src="https://github.com/user-attachments/assets/b24167a1-a3a1-43db-921e-115e7f18673b" height="70%" width="70%" alt="Tenant.Subscription"/>
 
- Your Resource Groups are where your resources go, in this case we will be using the <b>Azure Storage Account</b> service. This is just a storage that can hold various types of data.
<img src="https://github.com/user-attachments/assets/970f93f2-69e5-4c6f-b48b-c777dc016f6a" height="70%" width="70%" alt="Tenant.Subscription"/>
 


## Tools, Utilities, Services Used
- Microsoft Azure

## Environments Used 
- Windows 10

## Program walk-through




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

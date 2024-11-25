<p align="center">
     

</p>

<h1>Microsoft Azure</h1>
Azure is a cloud computing platform and an online portal that allows you to access and manage cloud services and resources provided by Microsoft. To get access to these resources and services, all you need to have is an active internet connection and the ability to connect to the Azure portal. This guide will demonstrate how to create an Azure account and create a virtual machine.

<h2>Requirements</h2>

- Computer with Internet Connection
- Credit Card (Required for free Azure credits)

<h2>Configuration Steps</h2>


<h3>Step 1: Create an Azure Account</h3>

- Select Start Free
- Follow the prompt to create the account 
     - You will need to put in your credit card information, but you will get $200 worth of Azure credit and will have 30 days to use those credits. You will not be charged until then
- Finish the prompt, click Go to Azure Portal, and you are ready to start with Azure!
     - You may also go to [portal.azure.com](https://www.portal.azure.com) to start

![Screenshot 2024-11-24 215051](https://github.com/user-attachments/assets/52ee6570-12bb-4f6a-b673-d5a45c27e7b5)




<h3>Step 2: Create a Resource Group</h3>

- Go to the search bar at the top and search "resource group"
- Select Create Resource Group
- You will need to name the resource group and select the region 
- Select Review + Create on the lower left
    - For this example, we will be using Web-vm for the name and (US) East US 2 for the region

![Screenshot 2024-11-24 215403](https://github.com/user-attachments/assets/0ac74596-7169-4c07-b20c-4eb1596062dd)




<h3>Step 3: Create a Storage Account</h3>

- Go to the search bar and search "storage account"
- Select Create Storage Account
- You will need to select the same resource group, the same region, and create a name for the storage group
    - For this example, we will name the storage group "rglab1"
    - Use the same resource group and region as step 2
- Select Review, then Create



![Screenshot 2024-11-24 215932](https://github.com/user-attachments/assets/b880adb5-0550-4f7c-a3fb-e2198a9fff01)



<h3>Step 4: Create a Virtual Machine</h3>
     
- Go to the search bar and search "virtual machine"
- Select Create, then select Azure Virtual Machine
- You will need to select the same resource group, the same region, and create a name for the virtual machine
    - For thise example, we will name the virtual machine "virtualmachine"
    - Use the same resource group and region as steps 2 and 3

![Screenshot 2024-11-24 215513](https://github.com/user-attachments/assets/ee0a9a8c-ba5b-48cf-9a1b-c451e856a9ec)

![Screenshot 2024-11-24 215525](https://github.com/user-attachments/assets/612bc7dd-b922-457b-a7d7-328550a2b6df)


![Screenshot 2024-11-24 215602](https://github.com/user-attachments/assets/41ab1e7e-01a5-4b3e-b949-16050448f1a9)



* You will then need to select the image and disk size
    - For image we will use Windows 10 Pro
    - For size, select See All Sizes and select Standard D2as_v4
* You will then need to make a username and password
    - For username, we will use "labuser"
    - Create your own password
* Click the box under licensing and finally click Review + Create 

![Screenshot 2024-11-24 220704](https://github.com/user-attachments/assets/769ca32c-744e-42f5-8790-f619c597e2f9)

![Screenshot 2024-11-24 220734](https://github.com/user-attachments/assets/32a508d6-391a-4132-b941-92280303c5c4)


![Screenshot 2024-11-24 220854](https://github.com/user-attachments/assets/21a6e24e-6781-4fd9-a151-d66d9c975e62)






 
     

<h3>Step 5: Connect to the Virtual Machine</h3>

- First, you will need to find the public IP address of your virtual machine
   - Select the virtual machine we created and the public IP address will be on the right-hand side of the screen
   - Copy the public IP address




* Mac Users 
   - Download Microsoft Remote Desktop
   - Open the application and click Add PC
   - Paste the public IP address and select Add
   - Double-click on the virtual machine and enter the username and password from step 4
   - Select Continue
   
* Windows Users
     - Open and use Remote Desktop
     - Paste the public IP Address and select Connect
     - Enter the username and password from step 4
     - Select OK







You have created your first virtual machine within Azure!





<p align="center">
     
![image](https://github.com/JustinPeguero/virtual-machine/assets/170198869/d3f91b83-0e3f-44b3-9316-1394b488bb6b)

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


 ![image](https://github.com/JustinPeguero/virtual-machine/assets/170198869/683a27fa-6560-49dd-bf22-b1c9ba29ffc8)
![image](https://github.com/JustinPeguero/virtual-machine/assets/170198869/9d498615-bbef-4155-9403-bdadc2de973a)



<h3>Step 2: Create a Resource Group</h3>

- Go to the search bar at the top and search "resource group"
- Select Create Resource Group
- You will need to name the resource group and select the region 
- Select Review + Create on the lower left
    - For this example, we will be using RG-Lab-1 for the name and (US) East US 2 for the region

![image](https://github.com/JustinPeguero/virtual-machine/assets/170198869/e0f1c1f4-f162-4a4f-9990-81248c9221b1)
![image](https://github.com/JustinPeguero/virtual-machine/assets/170198869/7b828305-259e-49da-af71-a8cf7af7e4d5)



<h3>Step 3: Create a Storage Account</h3>

- Go to the search bar and search "storage account"
- Select Create Storage Account
- You will need to select the same resource group, the same region, and create a name for the storage group
    - For this example, we will name the storage group "rglab1"
    - Use the same resource group and region as step 2
- Select Review, then Create

![image](https://github.com/JustinPeguero/virtual-machine/assets/170198869/91b03864-a0b8-4572-a124-20702b911024)
![image](https://github.com/JustinPeguero/virtual-machine/assets/170198869/d0e6dbfa-37e9-442d-b86c-b91a916287a3)




<h3>Step 4: Create a Virtual Machine</h3>
     
- Go to the search bar and search "virtual machine"
- Select Create, then select Azure Virtual Machine
- You will need to select the same resource group, the same region, and create a name for the virtual machine
    - For thise example, we will name the virtual machine "virtualmachine"
    - Use the same resource group and region as steps 2 and 3

![image](https://github.com/JustinPeguero/virtual-machine/assets/170198869/d34c6a17-1ecb-4dc0-b6c0-05992875858b)
![image](https://github.com/JustinPeguero/virtual-machine/assets/170198869/2a2eb7fb-93e1-4652-86fe-fdab55c4d339)





* You will then need to select the image and disk size
    - For image we will use Windows 10 Pro
    - For size, select See All Sizes and select Standard D2as_v4
* You will then need to make a username and password
    - For username, we will use "labuser"
    - Create your own password
* Click the box under licensing and finally click Review + Create 


![image](https://github.com/JustinPeguero/virtual-machine/assets/170198869/0d1a458c-6aee-4f21-8a24-b3a515c590ff)

 
     

<h3>Step 5: Connect to the Virtual Machine</h3>

- First, you will need to find the public IP address of your virtual machine
   - Select the virtual machine we created and the public IP address will be on the right-hand side of the screen
   - Copy the public IP address

![image](https://github.com/JustinPeguero/virtual-machine/assets/170198869/59119219-039a-4abf-a562-5566e5a9813b)


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
  
![image](https://github.com/JustinPeguero/virtual-machine/assets/170198869/cf223864-6c5d-4815-8e5f-268aecb0d09b)






You have created your first virtual machine within Azure!


<img src="https://i.imgur.com/rEBpL8Y.png" height="80%" width="80%" alt="Azure Free Account"/>


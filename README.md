<p align="center">
<img src="https://i.imgur.com/XzqzXiB.png">
</p>

<h1>Creating Resource Groups and Deploying Virtual Machines</h1>
This tutorial will outline the steps to creating a resource group and deploying two virtual machines in Azure.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines)
- Remote Desktop

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)
- Ubunto LT

<h2>Creating Resource Groups</h2>

<b> Select Resource Groups<b/>

<img src="https://i.imgur.com/setBBye.png"/>

<b> Select Create <b/>

<img src="https://i.imgur.com/rztZV56.png"/>
  
  
  <b> Name Resource Group and Select a Region </b>
  
  <img src="https://i.imgur.com/xVhoblW.png"/>
  
  <b> Once Validation Passed, Select Create </b>
  
  <img src="https://i.imgur.com/0ixROjh.png"/>
  
  <b> The Resource Group is Created successfully </b>
  
  <p> Now click the on the Virtual Machines. If you do not see it you can type in the search bar </p>
  
  <img src="https://i.imgur.com/XgDm7kE.png"/>
  
  <b> Click Azure Virtual Machine</b>
  
  <img src="https://i.imgur.com/1xrF7G0.png"/>
  
- Click the Resource Group that was created Earlier
- Name the Virtual Machine
- Select the region (should be the same as the resource group)
- Availablity Options (No Infrastructure redundancy required)
- Choose Standard size for Security Type 
- Select Windows 10 Pro under Image (Free Service Eligible)
  
  <img src="https://i.imgur.com/fAUecRA.png"/>
  
  <b>Create an username and password (Please remember the PW created will need for Remote Desktop)</b>

  <p>Click Review+Create at the bottom (Typically may not need to edit any of the other tabs)</p>
  
   <img src="https://i.imgur.com/9xMJ2IC.png"/>
  
  <b> Select Create </b>
  
  <img src="https://i.imgur.com/EIs8ojz.png"/>
  
  <b>Create the Second Virtual Machine</b>

  <p>This Virtual Machine will be the Domain Controller (Windows server 2022)</p>

- Make sure to select the Same Resource Group
- Select the Same Region
- Name the Virtual Machine (Something Similar to Remind you of the Domain Controller Ex DC1)
- Select Windows Server 2022
- Choose Standard Size
- Select a Username and Password 
  
  <img src="https://i.imgur.com/XQ5h0eY.png"/>
  <img src="https://i.imgur.com/44iQiEt.png"/>
  
  <h1> Log into the Virtual Machines Using Remote Desktop </h1>
  
- Log in using the specific Virtual Machines Public IP address (The Domain Controller and Client will have its own Public IP Address)
- Select Connect on the Remote Desktop
- Enter in Credentials from creating the Virtual Machines (Username & Password)
- Successfully Connected to each Virtual Machine
  
  <img src="https://i.imgur.com/ztCoY16.png"/>
  <img src="https://i.imgur.com/gyPBnyn.png"/>
  <img src="https://i.imgur.com/oidQoTu.png"/>
  <img src="https://i.imgur.com/78LmhzC.png"/>
  
  <h1> Utilizing Command Prompt (CMD) to check which Virtual Machine Is Logged In </h1>
  
- Type in "CMD" into the search bar
- Select Command Prompt
- Type in "hostname" into Command Line (This will allow you to see which machine is logged into)
  
  <img src="https://i.imgur.com/QH6FuvE.png"/>
  <img src="https://i.imgur.com/EP7Aflh.png"/>
  <img src="https://i.imgur.com/IrLeIQx.png"/>
  
  This will conclude the steps in this Project
  
  

  
  
  


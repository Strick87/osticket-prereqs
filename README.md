<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />





<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Create an Azure Virtual Machine Windows 10, 4 vCPUs
- Log into the VM with Remote Desktop, within the VM (osticket-vm), download the osTicket-Installation-Files.zip and unzip it onto your desktop.
- Configure IIS and Install Dependencies

 
- Install and Configure osTicket

- Finalize Database and Complete Installation
<h2>Installation Steps</h2>

![image](https://github.com/user-attachments/assets/3478f492-d3ea-4252-913b-1c024cb6da2e)




Prerequisite 1: Create a Virtual MachineThis screenshot demonstrates the process of setting up a virtual machine (VM) in Microsoft Azure. I am configuring a VM with Windows 10 as the operating system. The steps include selecting the subscription type, creating or choosing a resource group, naming the virtual machine, selecting a region, and configuring availability options. This process is essential for deploying virtual environments for development or testing purposes, showcasing my familiarity with cloud-based infrastructure and Azure services.




![image](https://github.com/user-attachments/assets/9471db84-c7eb-44d6-ac00-8e628ae8bd96)
![image](https://github.com/user-attachments/assets/11063232-7e58-4c30-bf3a-1ed9d4ff209a)





 Prerequisite 2: Access the VM and Prepare FilesConnecting to the Virtual Machine via Remote Desktop
This screenshot illustrates configuring a Remote Desktop connection to access the osticket-vm virtual machine. The public IP address of the VM is entered, and a friendly name (osTicket) is assigned for easy identification. This step ensures secure remote access to the VM, allowing me to proceed with downloading and unzipping the osTicket-Installation-Files.zip onto the desktop for further setup and configuration.
<br />


![image](https://github.com/user-attachments/assets/9a48ddc5-11ea-419e-b32f-b34fad3fb7b4)


<p>
</p>
<p>
Prerequisite 3: Configure IIS and Install DependenciesIn this step, I configured IIS (Internet Information Services) on the virtual machine to enable CGI and support PHP. I installed essential components, including PHP Manager for IIS, the Rewrite Module, and the Visual C++ Redistributable. Additionally, I created a C:\PHP directory and extracted PHP 7.3.8 files into it. These configurations are necessary for hosting and running osTicket smoothly.












![image](https://github.com/user-attachments/assets/e9e4a03e-953b-4c14-908d-e524e122a6d1)

</p>
<br />

<p>
Prerequisite 4: Install and Configure osTicketI set up osTicket by unzipping the installation files into C:\inetpub\wwwroot\osTicket, renaming the configuration file, and adjusting permissions. I also enabled required PHP extensions (php_imap.dll, php_intl.dll, and php_opcache.dll) in IIS to ensure proper functionality.

![image](https://github.com/user-attachments/assets/b7d35079-b73d-4af9-ac1d-4bc233161ac5)

Prerequisite 5: Finalize osTicket Installation
I completed the osTicket installation by ensuring all required and recommended prerequisites were met. This included verifying PHP extensions and configuring the system to prepare for database integration and final setup.


</p>
<br />

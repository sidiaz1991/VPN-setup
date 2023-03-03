<p align="center">
<img src="https://i.imgur.com/y4TF19i.jpg" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises VPN Setup and Usage (Proton VPN)</h1>
In this tutorial, we will set up an VPN inside of Azure Virtual machine. We  will use an public website called whatismypaddress to look up our Ipaddress for our PC. We will then browse within the Virtual machine and collect the ipaddress for the VM. At this point, we will have two different IPaddresses, and then we will download the free version of Proton VPN, where we will then connect to Japanese server or any country of your choice. We will then visit the whatismyaddress site for the third time to get the IPaddress for the country of your choice. This is good exercise on how to understand how VPN's works. <br />


- ### [](youtubelink)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- VPN proton
- whatismyipaddress (A public website we will used to collect the Ipaddress)

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)



<p>
<img src="https://i.imgur.com/AnD0KVM.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  
Browse to https://whatismyipaddress.com/ get IPaddress, This is where you will get the Ipaddress for your PC. Make sure to make note of it.
Log into the VM with Remote Desktop
Create a Vitrual machine in Azure if you have not already done so. This will require you to already have account set up with Microsoft Azure.
Create a resource group input all necessary information
Click on Vitrual machine in Azure to create a VM. (make sure to make note of username and password, this is what you use to signed in for remote desktop)
Create a Windows 10 Virtual machine in another geographic country or try a different country.
Once you created the VM, signed into remote desktop on your PC. (if you have Mac you will have to download remote desktop version since Mac does not come with it)

</p>
<br />

<p>
<img src="https://i.imgur.com/5ZUcSjI.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once you signed into the VM in the remote desktop. Collect the IPaddress from your Virtual machine. 
Clicked on overview and you will be able to collect the public address for your VM in Azure.
At this point, you should have used a different locaton for VM  
Visit Whatispaddress.com it will then give you IPaddress of your VM (make sure to keep note of this)  
  

</p>
<br />

<p>
<img src="https://i.imgur.com/gmmK2D4.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
On your PC not in your VM, sign up for the free version of Proton VPN https://account.protonvpn.com/signup?plan=free&language=en  
Back within your VM, download the Proton VPN client (Windows)
Login to the VPN and choose a VPN server in yet another country (such as Japan)
It will now be connected to VPN server in Japan
Browse to https://whatismyipaddress.com/ it will show now you are in Japan, since you connected to a VPN server in Japan.
Try browsing to Google, Disney, and/or Amazon and see if there is anything different about the sites in relation to the location of your VPN server. For example, the language or URL may be different.
</p>
<br />

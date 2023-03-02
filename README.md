<p align="center">
<img src="https://i.imgur.com/0AgAM6f.jpg" alt="Microsoft Active Directory Logo"/>
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
<img src="https://i.imgur.com/gmmK2D4.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Sign up for ProtonVPN and test the VPN connection)
On your actual computer, sign up for the free version of Proton VPN https://account.protonvpn.com/signup?plan=free&language=en  
Back within your VM, download the Proton VPN client
Login to the VPN and choose a VPN server in yet another country (such as Japan)
Browse to https://whatismyipaddress.com/  and take note of this in a text file
Try browsing to Google, Disney, and/or Amazon and see if there is anything different about the sites in relation to the location of your VPN server. For example, the language or URL may be different

</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

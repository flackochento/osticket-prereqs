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

- Resource group
- Virtual machine with 2-4 CPU'S
- Installation files
- Enabling IIS
- MySQL setup

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/WcEYwq2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The first step is to install the resource group in Azure followed by the virtual machine. Once created, we can begin to install the files neccessary for osticket inside of the virtual machine.
</p>
<br />

<p>
<img src="https://i.imgur.com/O9snNhd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
All the following files must be downloaded and installed inside of the virtual machine.MySQL is to be configured with a proper username and password in the correct database under the name "OsTicket".
</p>
<br />

<p>
<img src="https://i.imgur.com/zn3Pc5L.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Congratulations! Once complete, login into the OsTicket URL and it should work smoothly. Do a little clean up afterwards such as setting the permissions to "read only" for others and once complete, delete all resources inside of azure
</p>
<br />

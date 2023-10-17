# G1tavoi7
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Have an azure subscription
- create a VM and resource group in Azure
- Have remote desktop installed and have the creditials needed to login 

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/1HjmbYW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
This is the page that should load once you have installed IIS so you can run the osticketing systemto install you would need to go to control panel, then go to programs, windows features, and from there you would look for the IIS(Internet information services) file and have it checked off.  
</p>
<br />

<p>
<img src="https://i.imgur.com/BinQndr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
This is the osticketing system where I did the practice lab. In order to get to this page and have your osticketing system ready to go you would have need to install a couple things. PHP Manager, Rewrite Module,VC REDIST, MySQL. You can see some things have the red X's on them, just go the IIS, then PHP Manager and you will see disable/enable extensions. Just go down the list and chose which ones you ant and don't want.
</p>
<br />

<p>
<img src="https://i.imgur.com/Cv68Xm6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
So what you see on the right side is me setting up the OSticketing asking for email,first and last name, setting a password, and then at the bottom you see it asking about SQL database. For this you will have to dowload hediSQL, which is what you see on the left side. I created a data base called osticketing and then downloaded that file in the osticketing to use .
</p>

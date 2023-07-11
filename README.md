 # post-install-config
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
An effective helpdesk ticketing system allows organizations to record and regulate incoming support requests. 
This tutorial outlines the post-install configuration & Requirements of the open-source help desk ticketing system osTicket.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop
- Internet Information Services (IIS)
- Windows 10


<h2>Post-Install Configuration Requirements</h2>

- Connect to VM-1 using Remote Desktop
- Install and Enable IIS in Windows WITH CGI and Common HTTP Features
- Download and install PHP Manager for IIS 
- Download and install the Rewrite Module 
- Create the directory C:\PHP
- Download PHP 7.3.8 and unzip the contents into C:\PHP
- Download and install Visual C++
- Download and install MySQL 


<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/uPqaRnc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
STEP 1, You must log onto the VM that you created in Azure (VM-1) using Remote Desktop App. Use your VM's Public IP address & don't forget your password.
</p>
<br />

<p>
<img src="https://i.imgur.com/X4IsIxp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
STEP 2,  Install and Enable IIS in Windows WITH CGI on your VM (VM-1).
</p>
<br />

<p>
<img src="https://i.imgur.com/Aafqm7C.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
STEP 3,  Download and install PHP Manager for IIS on your VM (VM-1). 
</p>
<br />

<p>
<img src="https://i.imgur.com/GU87i6L.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
STEP 4, Download and install the Rewrite Module on your VM (VM-1).
</p>
<br />

<p>
<img src="https://i.imgur.com/jCNxabq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
STEP 5, Create the directory (folder) C:\PHP on your VM (VM-1) and then Download PHP and unzip the contents into that folder (C:\PHP) on  your VM (VM-1).
</p>
<br />

<p>
<img src="https://i.imgur.com/MuRNsrT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
STEP 6, Download and install Visual C++ on your VM (VM-1).
</p>
<br />

<p>
<img src="https://i.imgur.com/WYEqE8G.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
STEP 7, Download and install MySQL on your VM (VM-1). Then open Heidi SQL and Create a new session with the root/Password1. Then connect to the session & Create a database called “osTicket”.

Continue Setting up osticket in the browser
MySQL Database: osTicket
MySQL Username: root
MySQL Password: Password1
Click “Install Now!”

 
</p>
<br />


<p>
<img src="https://i.imgur.com/dIm3rA5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

Congratulations, hopefully it is installed with no errors!

  
</p>
<br />

<p>
<img src="https://i.imgur.com/cX65kex.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the image above, osTicket Login
</p>
<br />

<p>
<img src="https://i.imgur.com/yy9kNK5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Post-Install Configuration COMPLETE
</p>
<br />

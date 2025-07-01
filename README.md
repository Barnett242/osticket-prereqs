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

-Web Server: osTicket supports Apache or IIS web servers. 
PHP: Requires PHP version 8.1 or higher (8.2 is recommended). 
MySQL: Requires MySQL version 5.0 or higher. 
Operating System: osTicket is platform-independent, so it can be installed on various operating systems. 
Internet Access: Required for downloading files and potentially installing dependencies. 

<h2>Installation Steps</h2>

<p>
<img src=https://i.imgur.com/Ucn0s7C.png
</p>
<p>
Download osTicket: Obtain the latest version of osTicket from the official website. 
Server Setup: Install and configure necessary components like a web server (e.g., Apache, Nginx), PHP with required modules, and a database server (e.g., MariaDB, MySQL). 
Database Creation: Create a dedicated database and user for the osTicket installation. 
File Placement: Unzip the downloaded osTicket files and place them in the appropriate web server directory (e.g., /var/www/html for Ubuntu, wwwroot for Azure Windows VM). 
</p>
<br />

<p>
<img src=https://i.imgur.com/KGaQPYr.png
</p>
<p>
. Web-based Installation:
.
Access the osTicket installer through your web browser by navigating to the appropriate URL (e.g., https://your_server_ip/support) and follow the on-screen prompts to complete the installation and set up the Admin Panel.
</p>
<br />

<p>
<img src=https://i.imgur.com/eSuV2xc.png
</p>
<p>
2. Configure File Permissions:
.
After successful installation, adjust the permissions of the ost-config.php file to remove write access, as shown in the image, using methods like chmod (for CLI/FTP) or through a cPanel interface.
</p>
<br />

installing active directory tools on a windows server 2022 using hyper-v machine
Log in to the Windows Server
Open Server Manager and on the top right, click on Manage
Select Add Roles and Features
Click Next on Before you begin window
Select Role-based or feature-based installation and click Next
Click Next for Server Selection
Select Active Directory Domain Services from the options and click on Add Features and
click Next
 Keep clicking Next until you reach the confirmation page and click the Install button
 Wait for the Installation to finish and when it's finished, do not close the window yet
 Click on Promote the server to a domain controller
 Under Deployment Configuration window, select the Option Add a new forest and type in a
name in the Root domain name textbox (e.g seattle.com) and click Next
Type the admin password and click Next and Next until you reach Prerequisites Check Window
Once you see on top "All prerequisite checks passed successfully. " click the Install button and wait for it to finish and the computer will restart
Log in to the Windows server and you will now see the new Domain name we created and that means that Active Directory and Domain was successfully installed

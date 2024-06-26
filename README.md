<p align="center">
<img src="https://i.imgur.com/vaaWXxV.png"/>
</p>

<h1> Exploring Multiple Virtual Private Networks (VPN)</h1>
This tutorial outlines the exploration of multiple and international virtual private networks (vpn).<br />


<h2>Environments and Technologies Used</h2>

- Wi-fi Connection
- Microsoft Azure (Virtual Machines)
- Remote Desktop
- Google
- Proton VPN

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Local IP Address
- Resource Group
- Virtual Machine (Azure) with International VPN
- Remote Desktop
- International VPN
- Google Local Results
- Proton VPN

<h2>Local IP Address</h2>

<p>
<img src="https://i.imgur.com/xovernK.png"/>
</p>
<p>
Go to "whatismyipaddress.com".
</p>
<br />

<p>
<img src="https://i.imgur.com/Qu1NlGu.png"/>
</p>
<p>
Go to the Windows Pane. <br /> <br />
In the search bar type "Notepad". <br /> <br />
Document your local IP Address, City, State, and Country.<br /> <br />
</p>
<br />

<h2> Resource Group </h2>
<p>
<img src="https://i.imgur.com/mNCOzfD.png"/>
</p>
<p>
Go to Azure Portal "(Portal.Azure.com)". <br /> <br />
Log in with Azure credentials if you are not already logged in. <br /> <br />
Select "Resource Groups" icon. <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/gfA1u55.png"/>
</p>
<p>
Select the blue "Create" button.
</p>
<br />

<p>
<img src="https://i.imgur.com/koUP513.png"/>
</p>
<p>
Subscription: Select appropriate subscription if you have more than one subscription. <br /> <br />
If you only have one subscription skip this step and move on to the next. <br /> <br />
Resource Group: Select the desired Resource group name, for this tutorial we will be using "VPN". <br /> <br />
Region: Preferably select an international country you are not currently living in, for this tutorial we will be using "(Asia Pacific) Australia East". <br /> <br />
Select "Review + Create". <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/a5sb9rp.png"/>
</p>
<p>
Once all the steps have been completed correctly you should receive a green check mark with the words "Validation passed". <br /> <br />
Select the "Create" button to proceed. <br /> <br />
</p>
<br />

<h2> Virtual Machine (Azure) with International VPN </h2>
<p>
<img src="https://i.imgur.com/XhK5OVV.png"/>
</p>
<p>
Go to Azure Portal "(Portal.Azure.com)". <br /> <br />
Type "Virtual Machines" in the search bar. <br /> <br />
Select "Virtual Machines" from the search results. <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/NQGlThu.png"/>
</p>
<p>
Select "+ Create". <br /> <br />
Select "Azure virtual machine". <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/FSk06qC.png"/>
</p>
<p>
Subscription: Select appropriate subscription if you have more than one subscription. <br /> <br />
If you only have one subscription skip this step and move on to the next. <br /> <br />
Resource Group: Select the desired Resource group name, for this tutorial we will be using "VPN". <br /> <br />
Virtual machine name: Select the desired Virtual machine name, for this tutorial we will be using "VPN-1". <br /> <br />
Region: Select the desired region, for this tutorial we will be using "(Asia Pacific) Australia East". <br /> <br />
Availability Zone: Select the desired zone, for this tutorial we will be using "Zone 2". <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/tCR6z6v.png"/>
</p>
<p>
Image: Select the desired image, for this tutorial we will be using "Windows 10 Pro".
</p>
<br />

<p>
<img src="https://i.imgur.com/kJzYZTP.png"/>
</p>
<p>
Size: Select the desired size, for this tutorial we will be using "Standard - 2 vcpus". <br /> <br />
Username: Select the desired Username, for this tutorial we will be using "vpn-travel". <br /> <br />
Password: Create the desired password that you can easily remember or write down and easily retrieve. <br /> <br />
Confirm Password: Re-enter the password previously created. <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/HFjO9tO.png"/>
</p>
<p>
Acknowledge the Licensing Confirmation by check the box, it should turn blue. <br /> <br />
Select "Review + Create" to proceed with creating the virtual machine. <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/dFd09sQ.png"/>
</p>
<p>
Once all the steps have been completed correctly you should receive a green check mark with the words "Validation passed". <br /> <br />
Select the "Create" button to proceed. <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/Lm2YY0Z.png"/>
</p>
<p>
The deployment (creation) of the virtual machine is in process to be completed.
</p>
<br />

<p>
<img src="https://i.imgur.com/XhK5OVV.png"/>
</p>
<p>
Go to Azure Portal "(Portal.Azure.com)". <br /> <br />
Type "Virtual Machines" in the search bar. <br /> <br />
Select "Virtual Machines" from the search results. <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/oou0kH6.png"/>
</p>
<p>
Select "VPN-1".
</p>
<br />

<h2> Remote Desktop </h2>
<p>
<img src="https://i.imgur.com/AOK34Bd.png"/>
</p>
<p>
Copy Public IP Address. <br /> <br />
Go to the Windows Pane. <br /> <br />
Type "Remote Desktop Connection" in the search bar. <br /> <br />
Press "Enter". <br /> <br />
Paste Public IP Address. <br /> <br />
Select "Connect". <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/LVVsrjb.png"/> <img src="https://i.imgur.com/dv5oEiY.png"/>
</p>
<p>
Select "More choices". <br /> <br />
Select "Different account". <br /> <br />
Type Username, for this tutorial we will be using "vpn-travel". <br /> <br />
Type Password. <br /> <br />
Select "Ok". <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/qpk8xFg.png"/>
</p>
<p>
Select "Yes".
</p>
<br />

<p>
<img src="https://i.imgur.com/9S2xXaj.png"/>
</p>
<p>
Successfully connected to Remote Desktop Connection.
</p>
<br />

<h2> International VPN </h2>
<p>
<img src="https://i.imgur.com/DfqHEZw.png"/>
</p>
<p>
Open a new browser. <br /> <br />
Type "whatismyipaddress.com". <br /> <br />
Press "Enter". <br /> <br />
Observe the IP Address for Sydney, Australia based on the Region we selected while creating the virtual machine. <br /> <br />
</p>
<br />

<h2> Google Local Results </h2>
<p>
<img src="https://i.imgur.com/Q7cc5s1.png"/>
</p>
<p>
Go to "Google.com". <br /> <br />
Type "restaurants near me" in the search bar. <br /> <br />
Press "Enter". <br /> <br />
Observe the local search results since we are using a Sydney IP Address. <br /> <br />
</p>
<br />

<h2>Proton VPN </h2>
<p>
<img src="https://i.imgur.com/vOQSC0u.png"/>
</p>
<p>
Go to "Google.com". <br /> <br />
Type "protonvpn" in the search bar. <br /> <br />
Press "Enter". <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/lOgll9A.png"/>
</p>
<p>
Select "Proton VPN".
</p>
<br />

<p>
<img src="https://i.imgur.com/LV5pFOB.png"/>
</p>
<p>
Scroll down the page to find Free VPN. <br /> <br />
Select "free version". <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/crtVPh7.png"/>
</p>
<p>
Complete the Proton VPN Free Account Registration. <br /> <br />
Select "Downloads". <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/OCamw9Q.png"/>
</p>
<p>
Select the appropriate download, for this tutorial we will be using "Windows". <br /> <br />
Select "Download". <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/REF63q0.png"/>
</p>
<p>
Select "Download Proton VPN".
</p>
<br />

<p>
<img src="https://i.imgur.com/UIM1vC9.png"/>
</p>
<p>
Select "Open File".
</p>
<br />

<p>
<img src="https://i.imgur.com/Gd8zjko.png"/>
</p>
<p>
Select "Ok".
</p>
<br />

<p>
<img src="https://i.imgur.com/bGDMbOg.png"/>
</p>
<p>
Select "Next".
</p>
<br />

<p>
<img src="https://i.imgur.com/R4EiJEQ.png"/>
</p>
<p>
Select "Next".
</p>
<br />

<p>
<img src="https://i.imgur.com/jK2YnkV.png"/>
</p>
<p>
Select "Install".
</p>
<br />

<p>
<img src="https://i.imgur.com/Y6LtroW.png"/>
</p>
<p>
Installing Proton VPN and file extraction in progress.
</p>
<br />

<p>
<img src="https://i.imgur.com/PPUM4fW.png"/>
</p>
<p>
Enter Username. <br /> <br />
Enter Password. <br /> <br />
Select "Sign In". <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/sxiPrM1.png"/>
</p>
<p>
Select "Skip".
</p>
<br />

<p>
<img src="https://i.imgur.com/ZLOlbyz.png"/>
</p>
<p>
Select "Quick Connect".
</p>
<br />

<p>
<img src="https://i.imgur.com/33tbSsV.png"/>
</p>
<p>
Connected to Japanese IP Address.
</p>
<br />

<p>
<img src="https://i.imgur.com/lB4rtKz.png"/>
</p>
<p>
Go to "whatismyipaddress.com". <br /> <br />
Observe the IP Address from Shinjuku City, Japan based on our Proton VPN IP Connection. <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/2yPZzDe.png"/>
</p>
<p>
Open a new browser. <br /> <br />
Go to "Google.com". <br /> <br />
Type "apple" in the search bar. <br /> <br />
Press "Enter". <br /> <br />
Observe the search results are in Japanese. <br /> <br />
Congratulations you have completed this tutorial!. <br /> <br />
</p>
<br />

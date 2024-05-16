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
Go to Azure Portal (Portal.Azure.com). <br /> <br />
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
Select the Create button to proceed. <br /> <br />
</p>
<br />

<h2> Virtual Machine (Azure) with International VPN </h2>
<p>
<img src="https://i.imgur.com/XhK5OVV.png"/>
</p>
<p>
Go to Azure Portal (Portal.Azure.com). <br /> <br />
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
Select Review + Create to proceed with creating the virtual machine. <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/dFd09sQ.png"/>
</p>
<p>
Once all the steps have been completed correctly you should receive a green check mark with the words "Validation passed". <br /> <br />
Select the Create button to proceed. <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/Lm2YY0Z.png"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/XhK5OVV.png"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/oou0kH6.png"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<h2> Remote Desktop </h2>
<p>
<img src="https://i.imgur.com/AOK34Bd.png"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/LVVsrjb.png"/> <img src="https://i.imgur.com/dv5oEiY.png"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/qpk8xFg.png"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/9S2xXaj.png"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<h2> International VPN </h2>
<p>
<img src="https://i.imgur.com/DfqHEZw.png"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<h2> Google Local Results </h2>
<p>
<img src="https://i.imgur.com/Q7cc5s1.png"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<h2>Proton VPN </h2>
<p>
<img src="https://i.imgur.com/vOQSC0u.png"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/lOgll9A.png"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/LV5pFOB.png"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/crtVPh7.png"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/OCamw9Q.png"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/REF63q0.png"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/UIM1vC9.png"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/Gd8zjko.png"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/bGDMbOg.png"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/R4EiJEQ.png"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/jK2YnkV.png"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/Y6LtroW.png"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/PPUM4fW.png"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/sxiPrM1.png"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/ZLOlbyz.png"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/33tbSsV.png"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/lB4rtKz.png"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/2yPZzDe.png"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

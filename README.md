<h1>SEIM in Azure</h1>


<h2>Description</h2>
In this lab i set up a SIEM using Azure. I first set up a Virtual Machine in Azure and turned off the firewalls on the machine. I then expose the Virtual Machine to the internet so i can see live attacks from hackers all over the world. All attacks are tracked in a log file which is then extracted into Azure Sentinel. Sentinel allows us to plot the live attacks on a world map so we can visually see where these attacks are coming from as well as their severity.
<br />


<h2>Exposure to:</h2>

- <b>Azure Portal</b> 
- <b>Azure Sentinel</b>
- <b>Kusto Query Language (KQL)</b>
- <b>Network Security Groups</b>

<h2>Environments Used </h2>

- <b>Microsoft Azure</b>
- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Create VM In Azure: <br/>
<img src="https://i.imgur.com/XJC2A5X.png" height="80%" width="80%" alt="SIEM Steps"/>
<br />
<br />
Allow All in Firefox:  <br/>
<img src="https://i.imgur.com/VmFCaTK.png" height="80%" width="80%" alt="SIEM Steps"/>
<img src="https://i.imgur.com/ggnyDte.png" height="80%" width="80%" alt="SIEM Steps"/>
<br />
<br />
Create Log Analytics Workspace: <br/>
<img src="https://i.imgur.com/ssFHNmQ.png" height="80%" width="80%" alt="SIEM Steps"/>
<br />
<br />
Enable Gathering of VM Logs From Security Center In Azure:  <br/>
<img src="https://i.imgur.com/jUIVcKQ.png" height="80%" width="80%" alt="SIEM Steps"/>
<br />
<br />
Connect Log Analytics to VM:  <br/>
<img src="https://i.imgur.com/FQ3tVb0.png" height="80%" width="80%" alt="SIEM Steps"/>
<br />
<br />
Setup Azure Sentinel:  <br/>
<img src="https://i.imgur.com/pXPyMzg.png" height="80%" width="80%" alt="SIEM Steps"/>
<br />
<br />
Log Into Azure VM with Remote Desktop:  <br/>
 <img src="https://i.imgur.com/vNsJ1Jr.png" height="80%" width="80%" alt="SIEM Steps"/>
<br />
<br />
Turn Off Windows Firewall for VM:  <br/>
<img src="https://i.imgur.com/rbdUHTt.png" height="80%" width="80%" alt="SIEM Steps"/>
<br />
<br />
Set Up PowerShell Script to get Geolocation of Logs Using Geolocation API: <br/>
<img src="https://i.imgur.com/9G4Wymd.png" height="80%" width="80%" alt="SIEM Steps"/>
<br />
<br />
Create Custom Log in Log Analytics Workspace and Import Our VM Logs:  <br/>
<img src="https://i.imgur.com/GSn8XHW.png" height="80%" width="80%" alt="SIEM Steps"/>
<img src="https://i.imgur.com/qkH2Nwz.png" height="80%" width="80%" alt="SIEM Steps"/>
<br />
<br />
Create Customs Fields to Extract to Be Extracted From Imported Logs:  <br/>
<img src="https://i.imgur.com/q9NOR4m.png" height="80%" width="80%" alt="SIEM Steps"/>
<img src="https://i.imgur.com/WQQWBKh.png" height="80%" width="80%" alt="SIEM Steps"/>
<img src="https://i.imgur.com/AJSXBCB.png" height="80%" width="80%" alt="SIEM Steps"/>
<img src="https://i.imgur.com/zGCiEFp.png" height="80%" width="80%" alt="SIEM Steps"/>
<br />
<br />
Setup Map in Sentinel With Latitude and Longitude:  <br/>
<img src="https://i.imgur.com/iOxjqr8.png" height="80%" width="80%" alt="SIEM Steps"/>
<br />
<br />
Live Map Showing All Attacks And Their Locations:  <br/>
<img src="https://i.imgur.com/SFsL8iE.png" height="80%" width="80%" alt="SIEM Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>

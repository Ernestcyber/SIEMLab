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
Launch the utility: <br/>
<img src="https://imgur.com/a/X9ksWuF"/>
<br />
<br />
Select the disk:  <br/>
<img src=""/>
<br />
<br />
Enter the number of passes: <br/>
<img src=""/>
<br />
<br />
Confirm your selection:  <br/>
<img src=""/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src=""/>
<br />
<br />
Sanitization complete:  <br/>
<img src=""/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src=""/>
 Launch the utility: <br/>
<img src=""/>
<br />
<br />
Select the disk:  <br/>
<img src=""/>
<br />
<br />
Enter the number of passes: <br/>
<img src=""/>
<br />
<br />
Confirm your selection:  <br/>
<img src=""/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src=""/>
<br />
<br />
Sanitization complete:  <br/>
<img src=""/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src=""/>
 Launch the utility: <br/>
<img src=""/>
<br />
<br />
Select the disk:  <br/>
<img src=""/>
<br />
<br />
Enter the number of passes: <br/>
<img src=""/>
<br />
<br />
Confirm your selection:  <br/>
<img src=""/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src=""/>
<br />
<br />
Sanitization complete:  <br/>
<img src=""/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src=""/>
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

<h1>Nessus Trainng</h1>


<h2>Description</h2>
I decided to do some training on vulnerability management with Nessus and VMWare Workstation Player. I do work with a closely related tool (Tenable) for my job, so I wanted to try some preliminary tasks with Nessus due to it being such a staple in the community of security. I started with downloading VMWare Player 17 and used the same Windows 10 ISO for the VM as the Active Directory Lab, from there I followed a step-by-step process in order to establish a connection with Nessus as well as run a series of varying simple scans to assess the security of the VM. After this, I worked towards remediating some of the larger vulnerabilites to see the changes in the scan results.  
<br />


<h2>Languages and Utilities Used</h2>

- <b>Nessus Essentials</b> 
- <b>VMWare Workstation Player 17</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)


<h2>Lab Screenshots</h2>

<p align="center">
Successfully downloaded and configured Nessus Essentials on my home machine: <br/> <br />
<img src="https://i.imgur.com/0BJuuTo.png" height="80%" width="80%" alt="Lab Screenshots"/>
<br />
<br />
Turning off VM firewall in order to establish connection to Nessus on home machine: <br/> <br />
<img src="https://i.imgur.com/H640wds.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Connection attempts where the first is with the firewall enabled and the second is with the firewall disabled: <br/> <br />
<img src="https://i.imgur.com/EjTb0k6.png" height="80%" width="80%" alt="Lab Screenshots"/>
<br />
<br />
Results of simple uncredentialed scan on VM in Nessus after establishing connection: <br/> <br />
<img src="https://i.imgur.com/CE9VJs6.png" height="80%" width="80%" alt="Lab Screenshots"/>
<br />
<br />
After this, I ran a scan with the credentials of the account made on the VM: <br/> <br />
<img src="https://i.imgur.com/Zg9QMrx.png" height="80%" width="80%" alt="Lab Screenshots"/>
<br />
<br />
I then downloaded a very old version of Firefox (3.6.12) on the VM and ran another credentialed scan: <br/> <br />
<img src="https://i.imgur.com/oCArjO7.png" height="80%" width="80%" alt="Lab Screenshots"/>
<br />
<br />
Now I attempted to remediate these as best I could, which began with deleting Firefox from the VM: <br/> <br />
<img src="https://i.imgur.com/v4PVgGb.png" height="80%" width="80%" alt="Lab Screenshots"/>
<br />
<br />
The next simple step was running Windows update on the VM repeatedly until up to date: <br/> <br />
<img src="https://i.imgur.com/hH5FBjs.png" height="80%" width="80%" alt="Lab Screenshots"/>
<br />
<br />
I then ran a final credentialed scan to see the results of the remediation: <br/> <br />
<img src="https://i.imgur.com/fRRMuJ5.png" height="80%" width="80%" alt="Lab Screenshots"/>
<br />
<br />
Here are all the scans put together: <br/> <br />
<img src="https://i.imgur.com/ggVZu8Y.png" height="80%" width="80%" alt="Lab Screenshots"/>
<br />
<br /> 
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

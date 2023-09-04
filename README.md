<h1>Network Scanning in Tenable Nessus</h1>



<h2>Description</h2>
This project consists of utilizing the open source tool Tenable Nessus to conduct a vulnerability scan of the devices found on my network and being able to identify the solutions available to mitigate those risks.
<br />


<h2>Utilities Used</h2>

- <b>Tenable Nessus</b> 


<h2>Environments Used </h2>

- <b>Windows 10</b> (22H2)
- <b>Kali Linux Virtual Machine (VM)</b>

<h2>Program walk-through:</h2>

<p align="center">
Launch Kali Linux: <br/>
<img src="https://i.imgur.com/C3Wo5bS.png" height="80%" width="80%" alt="Kali Linux VM startup"/>
<br />
<br />
Install Nessus in the VM:  <br/>
<img src="https://i.imgur.com/TWdb1Yk.png" height="80%" width="80%" alt="Install Nessus software"/>
<br />
<br />
Save file to desktop as nessus.deb: <br/>
<img src="https://i.imgur.com/evBIvcm.png" height="80%" width="80%" alt="Save file to desktop"/>
<br />
<br />
Open command line and change directory (cd) to desktop:  <br/>
<img src="https://i.imgur.com/zRH7zv5.png" height="80%" width="80%" alt="Change directory"/>
<br />
<br />
Install nessus package in command line:  <br/>
<img src="https://i.imgur.com/7jqxb4A.png" height="80%" width="80%" alt="Install package"/>
<br />
<br />
After successful installation, run the service:  <br/>
<img src="https://i.imgur.com/eHbn3yL.png" height="80%" width="80%" alt="Run Nessus service"/>
<br />
<br />
Navigate to Firefox and open Nessus to configure scanner, you can advance past the warning:  <br/>
<img src="https://i.imgur.com/8nqllpO.png" height="80%" width="80%" alt="Go to Nessus in Firefox"/>
<br />
<br />
Create your account:  <br/>
<img src="https://i.imgur.com/kHY2wG9.png" height="80%" width="80%" alt="Create Nessus account"/>
<br />
<br />
Conduct a host discovery scan to discover devices on your network:  <br/>
<img src="https://i.imgur.com/p8XvXsn.png" height="80%" width="80%" alt="Conduct host discovery"/>
<br />
<br />
Observe the host(s) that were identified on the network and any ports being used:  <br/>
<img src="https://i.imgur.com/AhY5mJg.png" height="80%" width="80%" alt="Observe host on network"/>
<br />
<br />
Configure a scan of the device(s) on the network:  <br/>
<img src="https://i.imgur.com/YTxv6mD.png" height="80%" width="80%" alt="Basic network scan"/>
<br />
<br />
Observe the vulnerabilities that were identified:  <br/>
<img src="https://i.imgur.com/55MNExo.png" height="80%" width="80%" alt="Observe vulnerabilities"/>
<br />
<br />
Further look of vulnerabilities on a host:  <br/>
<img src="https://i.imgur.com/G88Zoko.png" height="80%" width="80%" alt="Further look at vulnerabilities"/>
<br />
<br />
In-depth analysis of vulnerability and solution:  <br/>
<img src="https://i.imgur.com/qHbznuO.png" height="80%" width="80%" alt="In-depth analysis and solution"/>

  
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

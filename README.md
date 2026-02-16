<h1>DHCP</h1>

<h2>Description</h2>
This project consists of creating a basic DHCP configuration where I was asked, in a simulated ticket, to create a scope of IP addresses.
<br />
<h2>Settings</h2>
<br />
Network: 192.168.50.0/24

Address range: 192.168.50.100 – 192.168.50.200

Exclusion range: 192.168.50.150 – 192.168.50.160

Lease duration: 10 hours
<br />


<h2>Environments Used </h2>

- <b>Windows server 2025</b>
<br />
Here we create the range of Ip addresses and assign the subnet mask <br/>
<img src="https://i.imgur.com/tYjAd6I.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
The exclusion range prevents IP conflicts with statically assigned devices<br/>
<img src="https://i.imgur.com/TuMJICg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Reducing lease time allows faster reassignment during testing.<br/>
<img src="https://i.imgur.com/nzZR8r0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Configured a DHCP scope to dynamically assign IP addresses<br/>
<img src="https://i.imgur.com/mwFT6DY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />



<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>

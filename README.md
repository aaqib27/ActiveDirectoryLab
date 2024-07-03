<h1>Active Directory Administration and Automation Lab</h1>

<h2>Description</h2>

###
This project involves creating an Active Directory and network administration environment using PowerShell automation, remote access server (RAS) configuration, and Windows server management. Configuring and running this environment will enhance your understanding of Active Directory and Windows networking. PowerShell scripts can be developed and implemented to automate the provisioning, maintenance, and de-provisioning of user accounts within Active Directory, streamlining account management processes. We configure RAS features to support Network Address Translation (NAT) and Port Address Translation (PAT), enhancing remote access capabilities for secure network connections. Additionally, Windows DNS and DHCP services are managed to ensure robust and autonomous network address management, and Windows File Servers are configured with quotas and NTFS permissions to maintain secure and organized file storage.

###
This project demonstrates critical network administration tasks and automation techniques, providing valuable hands-on experience in managing Active Directory and Windows networking environments.



<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Active Directory</b>
- <b>Oracle VM VirtualBox</b>

<h2>Environments Used </h2>

- <b>Windows 10 (22H2)</b> (Used for CLIENT1 VM)
- <b>Windows Server 2019</b> (Used for Domain Controller VM)

<h2>Screenshots of Key Stages:</h2>

<p align="center">
1. Administrator account connected to the domain - mydomain.com: <br/>
<img src="https://i.imgur.com/VZNdNIK.jpeg" height="80%" width="80%" alt="Active Directory Administration Steps"/>
<br />
<br />
2. Create a new Admin User in AD _ADMINS Organizational Unit (OU):  <br/>
<img src="https://i.imgur.com/Lmnj1XG.jpeg" height="80%" width="80%" alt="Active Directory Administration Steps"/>
<br />
<br />
3. Logging into the Newly Created User: <br/>
<img src="https://i.imgur.com/VUwAK8A.jpeg" height="80%" width="80%" alt="Active Directory Administration Steps"/>
<br />
<br />
4. Configuring RAS for NAT and PAT:  <br/>
<img src="https://i.imgur.com/w9QEE7o.jpeg" height="80%" width="80%" alt="Active Directory Administration Steps"/>
<br />
<br />
5. Setting up DHCP:  <br/>
<img src="https://i.imgur.com/WdhgMp8.jpeg" height="80%" width="80%" alt="Active Directory Administration Steps"/>
<br />
<br />
6. Run PowerShell Script to Create 1k+ Users in AD:  <br/>
<img src="https://i.imgur.com/CrhIES1.jpeg" height="80%" width="80%" alt="Active Directory Administration Steps"/>
<br />
<br />
7. Overview of 1k+ Created Users in AD using PS script:  <br/>
<img src="https://i.imgur.com/qpUVPKU.jpeg" height="80%" width="80%" alt="Active Directory Administration Steps"/>
<br />
<br />
8. Check if "CLIENT1" is connected to default gateway and joined to domain:  <br/>
<img src="https://i.imgur.com/bvpin7v.jpeg" height="80%" width="80%" alt="Active Directory Administration Steps"/>
<br />
<br />
9. "CLIENT1" gets assigned an IP address by the DHCP server:  <br/>
<img src="https://i.imgur.com/opoV54e.jpeg" height="80%" width="80%" alt="Active Directory Administration Steps"/>
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

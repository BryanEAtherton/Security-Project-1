# Security-Project-1

<p align="center">
<img src="https://i.imgur.com/NNk2ICv.jpg"/>
</p>

<h1>Azure Virtual Machine Setup</h1>
Here we will set up 2 Azure Virtual Machines,1 Windows & 1 Linux, to use in our Security Project .<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure
- Azure Network Security Groups (NSG)

<h2>Operating Systems Used </h2>

- Windows 10</b> 
- Linux (Ubuntu)</b> 

<h2>Virtulal Machine Setup </h2>


<h2>Initial Setup</h2>

<p>
<img src="https://i.imgur.com/QSn0enR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
1.  In Azure Create 2 VMs - 1 Windows & 1 Linux. 
  
[Click here to view instructions on how to create and access an Azure VM using Remote Desktop](https://github.com/BryanEAtherton/Azure-Virtual-Machine)
</p>

 <p>
2. Navigate to the Linux VM NSG and disable the Firewall by deleting the SSH inbound rule. 
 <p>
<img src="https://i.imgur.com/CCWUnuQ.png" height="50%" width="40%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/E7EQyPj.png" height="50%" width="40%" alt="Disk Sanitization Steps"/>
 </p>

<p>
 3. Create a new rule to allow all traffic into the VM.
<p>
<img src="https://i.imgur.com/3NPTV98.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/8iTnSg6.png" height="50%" width="40%" alt="Disk Sanitization Steps"/>
 <p>
4. 
</p>
<br />

<p>
<img src="https://i.imgur.com/wvBSxBf.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/TEEgHIo.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>
<p>
5. Fill out the appropiate fields and select an OS for the VM
  
6. Continue by selecting the size of the cpu you want and assign the VM a username and password
</p>
<br />

<p>
<img src="https://i.imgur.com/ZByAEPt.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/e826w1a.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>
<p>
7. Check the box to confirm licensing and select Review + Create
  
  8. Once Validation has passed select the Create button
</p>
<br />

<h2>VM Access Steps</h2>
<p>
<img src="https://i.imgur.com/SeLhFq2.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/O460gZt.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>
<p>
9. Navigate to the VM information in Azure and locate the Public IP Address

  10. Use ip address to remote connect to the VM
</p>
<br />

<p>
<img src="https://i.imgur.com/ur3TdEq.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/xHJ2rDu.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>
<p>
11. Enter username and password from setup (Step 6)

  12. Remote Desktop Home screen
</p>
<br />





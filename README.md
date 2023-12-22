<p align="center">
<img src="https://i.imgur.com/MaIKufJ.png"/>
</p>

<h2>Summary</h2>
<p>This is a walk-through on how to use Microsoft Azure to create Virtual Machines (VMs), it shows step-by-step how to create an Azure account and proceed from that to making Vms in the cloud and logging in remotely. The environments used are Azure, Windows 10, and Remote Desktop connection. </p>


<h2>Azure Compute and Networking - Prerequisites and Installation</h2>

- laptop (or any device with access to the web)
- email
- credit card (azure is free but requieres a CC as a method of verification)
- Sms number (for sms verification)


<h2>Setup</h2>
<p>
<img src="https://i.imgur.com/inK4MMS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Head over to microsft azure and sign up by clicking the green start free button. Input the information asked for i.e. (email, name, ect).
</p>
<br />

<p>
<img src="https://i.imgur.com/0rGLLBE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After completing the registery you will be redirected to a new page. Click the blue azure portal button, and you've successfully setup an azure account with a free 200 credits.
</p>
<br />


<h2>Adding your first virtual desktop</h2>
<p>
<img src="https://i.imgur.com/Ek5ATXG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once in the azure menu search (virtual machines) in the search bar at the top. after clicking on VM's (virtual machines) click create, then select azure VM.
</p>
<br />



<p>
<img src="https://i.imgur.com/KQPDqCD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Name your VM doesnt need to be anything spesific i.e. VM-1.
</p>
<br />


<p>
<img src="https://i.imgur.com/vLWi8aE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Select Windows 10 as the image. For the size the more virtual CPUs (VCPUs) the faster the virtual desktop will be (Using 1 vcpus is not recommended for it's very slow). make a username and password (dont forget it). At the bottom check the licensing box and hit review and create.
</p>
<br />


<p>
<img src="https://i.imgur.com/W74mRl4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
If everything was done correctly it should say validation passed and you can click the blue create button.
</p>
<br />


<p>
<img src="https://i.imgur.com/X3t2LZ8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After waiting for azure to finish creating your VM, if you search VM again you should see the VM you created.
</p>
<br />

<h2>Connecting to your VM</h2>
<p>
<img src="https://i.imgur.com/sc2326t.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now by clicking on it you should see all of the VMs info, we'll be needing this to RDC (remote desktop connection) into it. we are going to need the public ip of the VM.
</p>
<br />


<p>
<img src="https://i.imgur.com/Xw7fpFF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Hit the Windows key and open Remote Desktop connection. input the Public IP from our VM and click connect.
</p>
<br />


<p>
<img src="https://i.imgur.com/KvSsTP0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Input the username and password we made for our VM and click ok. If successful a warning will apear, click yes
</p>
<br />


<p>
<img src="https://i.imgur.com/wVsMeKV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click yes, and If everything was done right, then congratulations you've seccussfully created a VM. Theres is alot of information about azure i skipped over (recourse groups, network interface cards, ect) for the sake of simplicity, this is the bare minume needed to create a VM.  i highly recommend reading or even watching some youtube videos about azure on the things i named.
</p>
<br />

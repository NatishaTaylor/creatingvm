<p align="center">
<img src="https://i.imgur.com/En7CjhB.png" height="60%" width="50%"
</p>

</p>
<h1>Creating a Virtual Machine (VM) in Microsoft Azure</h1>

Welcome!!! In this project I will show a tutorial on how to make a Virtual Machine (vm) in Mircrosoft Azure <br />
*Included Network Watcher and Topology* <br>


<h2>Requirements</h2>

- Computer with internet connection
- Microsoft Azure account
  - Credit card (required for free Azure credits)

<h2>Advanced Steps</h2>

- Log into  [Microsoft Azure](https://portal.azure.com/)
- Select “Virtual machines” and select to Create an “Azure virtual machine”
- Fill in the required fields on the “Basics” page
- Click “Review + create”
- Click “Create” if the VM has passed validation
- View newly created VM in Network Watcher
- Delete Resource Groups to minimize charges to free Azure credits

<h2>Synopsis</h2>

<p><br>
After you log in
<img src="https://i.imgur.com/BetIXPn.png" height="70%" width="70%"/>
<p>
<p><br>

<img src="https://i.imgur.com/ph8Vhx2.png" height="70%" width="70%"/>
</p>
<p>
To get started on creating the virtual machine, I searched for “virtual machine” in the search bar at the top of the Azure homepage and selected “Virtual machines.” I clicked “Create” in the top left corner (the blue “Create” button in the middle of the screen also works) and then selected “Azure virtual machine.”
</p>
<br />

<p>
<img src="https://i.imgur.com/7PFkY2F.png" height="50%" width="50%"/>
</p>
<p>
<img src="https://i.imgur.com/cZCe81m.png" height="50%" width="50%"/>
</p>
<p>
The first page is the “Basics” page, where I filled in the required fields. For the Resource group, I made a new one by selecting “Create new” and also selected an appropriate region based on my location. The location you select can affect your options for the “Size” field, so this may need to be tinkered with a little. Image is the base operating system or application for the VM. I used Windows 10 in this example. Don’t forget to check the box under Licensing! Once I was done filling this page out, I clicked “Review + create.”
</p>
<br />

<p>
<img src="https://i.imgur.com/9AxM3vR.png" height="50%" width="50%"/>
</p>
<p>
Before the VM could be created, I had to make sure it passed validation. Once the message at the top confirmed that everything was set up properly, I clicked “Create.”
</p>
<br />

<p>
<img src="https://i.imgur.com/3iB9u1P.png" height="70%" width="70%"/>
</p>
<p>
It took a bit of time for the VM to be set up by Azure, but once it was done, I was able to look at the configuration of my VM. I made a mental note of the location of the public and private IP addresses on this page, since finding this information would be important for using remote help desk and VPN usage.
</p>
<br />

<p>
<img src="https://i.imgur.com/J9BB8fA.png" height="70%" width="70%"/>
</p>
<p>
View the various components of my new VM using Network Watcher in Azure. As you can see, when you create a VM, it’s not just the virtual machine itself that is created. Along with the VM (VM-1), Azure also created a virtual network (VM-Lab-vnet), a subnet (default), a virtual NIC (vm-1960), a Network Security Group as known as the firewall (VM-1-nsg), and a public IP address (VM-1-ip).
</p>
<br />

<p>
*Don’t forget to delete any Resource groups that were created if you want to minimize the charges to your free Azure credits.*
</p>
<br />

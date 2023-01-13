# azure-network-protocols  

<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this project we observe the flow of network traffic and connection between two Virtual Machines. <br />
<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Create Resourses 
- Remote into the Virtual Machines
- Observe Network Traffic
- Set up Firewall to stop traffic

<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/huh1Xsw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create a Resource Group then, Create a Windows 10 Virtual Machine and Create a Linux (Ubuntu) VM then remote into the Windows VM. When you are in the VM, you should download Wireshark. Wireshark allows you observe the traffic between different computers.
</p>
<br />

<p>
<img src="https://i.imgur.com/TddQ7iN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
This image above represents the traffic between networks. With this turtorial, you should ping the IP address of the other virtual machine that was uploaded and you should see a good connectivity between the two computers.  
</p>
<br />

<p>
<img src="https://i.imgur.com/L4oJqAR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Using NSG(Network Security Group)is essentially the same as building a firewll on The cloud(Azure). During this tutorial, You will set up the firewall to deny protocols and it will stop traffic from coming in within the two VM's.
</p>
<br />


<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />


<h2>Video Demonstration</h2>

- ### [YouTube: Azure Virtual Machines, Wireshark, and Network Security Groups](https://www.youtube.com)

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

- Step 1: Provision Azure Virtual Machines: Deploy Windows and Linux VMs in the same Virtual Network and subnet.
- Step 2: Capture Network Traffic with Wireshark: Installed and used Wireshark to analyze network traffic between VMs.
- Step 3: Configure Network Security Groups: Set up NSGs to manage inbound and outbound traffic.
- Step 4: Adjust NSG Rules and Analyze Results: Modified NSG rules and observed changes using Wireshark.

<h2>Actions and Observations</h2>

<p>
<img <img width="1917" height="971" alt="image" src="https://github.com/user-attachments/assets/19b1cf7a-45dc-412a-92fc-3db7f1e01bdb" />
<img <img width="1918" height="973" alt="image" src="https://github.com/user-attachments/assets/62a88e88-8af1-430b-abf2-f8388cf85b47" />


</p>
<p>
Azure portal resource group overview page displaying both Windows and Linux virtual machines (VMs) listed as resources. The details panel shows both VMs assigned to the same virtual network and subnet, confirming successful deployment and network configuration.
</p>
<br />

<p>
<img <img width="1912" height="1007" alt="image" src="https://github.com/user-attachments/assets/b75ba4cf-13ae-41f4-982b-17a349205e2b" />

</p>
<p>
Demonstrated above is a remote desktop session into the Windows VM. Wireshark is open and actively capturing ICMP packets. Windows PowerShell is visible, running the ping command to the Linux VM’s private IP address. Therefore showing captured packets in Wireshark, corresponding to the ongoing ping traffic between the Windows and Linux virtual machines, demonstrating successful network communication and packet inspection.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

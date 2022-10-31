# Network-security-Groups<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />




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

- Step 1
- Step 2
- Step 3


<h2>Actions and Observations</h2>

<p>
<img src="https://user-images.githubusercontent.com/116759326/198902984-67207e36-4695-440a-ba7e-a51cb34ec862.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 You can use an Azure network security group to filter network traffic to and from Azure resources in an Azure virtual network. A network security group contains security rules that allow or deny inbound network traffic to, or outbound network traffic from, several types of Azure resources. Network security groups are associated to subnets or to virtual machines and cloud services deployed in the classic deployment model, and to subnets or network interfaces in the Resource Manager deployment model.

</p>
<br />

<p>
<img src="https://user-images.githubusercontent.com/116759326/198903475-1892e2f9-9318-431d-9516-e57d3a375662.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
This is demonstrating inbound and outboung traffic via (NSG) Network Security Groups.For inbound/outbound traffic Azure processes the rules in a network security group associated to a subnet first, if there's one, and then the rules in a network security group associated to the network interface, if there's one. 
</p>
<br />

<p>
<img src="https://user-images.githubusercontent.com/116759326/198904739-03557445-5184-4268-a13b-70b131d5ea86.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Application security groups enable you to configure network security as a natural extension of an application's structure, allowing you to group virtual machines and define network security policies based on those groups.
 Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP):
 IP stands for Internet Protocol. This protocol works with TCP and UDP protocols. It provides a unique identity to each node on the computer network.
 DNS stands for Domain Name Service. This service allows us to access a node by its name. By default, nodes use IP addresses to identify each other on the network.
 NAT stands for Network Address Translation. This protocol translates one IP address to another. This can be a source address or a destination address. Two basic implementations of NAT can be used: static and dynamic. In the static NAT, a manual translation is performed.
 Simple Network Management Protocol is a TCP/IP protocol for monitoring networks and network components. SNMP uses small utility programs called agents to monitor behavior and traffic on the network. 
 SMB is a file-sharing protocol. It allows networked computers to transparently access files that reside on remote systems over a variety of networks.
 FTP runs over TCP, which provides a connection-oriented, guaranteed data-delivery service. FTP is a character-based command interface, although many FTP applications have graphical interfaces.
 TFTP is used when a file transfer does not require an acknowledgment packet during file transfer. TFTP is used often in the router configuration. 
 
 
</p>
<br />


<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

# Inspecting-Network-Protocols Between azure virtual machines
In this tutorial, we observe various traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />




<h2>Environments and Technologies Used</h2>

-  Microsoft Azure (Virtual Machines)
-  Remote Desktop
-  Various Commmand-Line Tools
-  Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>The Set-Up</h2>

<p>
</p>
<p>
Within Azure, I created two VMs within the same Virtual network to ensure that they are able to communicate with each other. One VM will have windows 10 Pro while the other uses Ubuntu. The Windows VM will connect to the other via the command line/PowerShell.

<h2>Actions and Observations</h2>




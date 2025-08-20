# Network-Security-Groups-NSGs-and-Inspecting-Network-Protocols
<p align="center">
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

- Step 1 -Create an Azure Storage Account
- Step 2 -Create a File Share
- Step 3 -Configure Access Permissions
- Step 4 -Test User Access to The File Share

<h2>Actions and Observations</h2>

<p>
<img width="1177" height="683" alt="image" src="https://github.com/user-attachments/assets/f85cd43c-597b-432f-a3ae-1854e44fb7f3" />

</p>
<p>
This section shows how to configure and set up the shared drive — perfect for capturing the initial setup steps.<br />

<p>
<img width="1176" height="679" alt="image" src="https://github.com/user-attachments/assets/651f6462-fbc2-4784-b04d-fb1a36911242" />

</p>
<p>
Here you’ll see how to assign user or group permissions to the shared folder — ideal for showing the security settings.
<br />

<p>
<img width="1178" height="643" alt="image" src="https://github.com/user-attachments/assets/d5302448-b5a5-40e9-9880-db79cdaf6ca1" />

</p>
<p>
This part covers creating a security group in Active Directory and linking it to the shared drive — great for showing how AD ties into file sharing.<br />

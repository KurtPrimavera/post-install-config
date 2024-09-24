<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket Post-Installation Specialist: Streamlining Configuration Processes</h1>
  This tutorial provides a comprehensive guide to the post-installation configuration of osTicket, an open-source help desk ticketing system designed to streamline support processes. It walks users through essential steps and best practices for configuring osTicket to maximize its potential. Readers will learn how to customize key settings, optimize user roles, and implement effective workflow management techniques. Additionally, the tutorial explores various features such as email piping, ticket management, and reporting tools that enhance the efficiency of help desk operations. Whether users are novices or experienced IT professionals, this tutorial equips them with the knowledge and skills necessary to ensure a successful setup and a smoother user experience for both support staff and customers.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute): Cloud platform for scalable computing resources.
- Remote Desktop Protocol (RDP): Protocol for secure remote access to desktop environments.
- Internet Information Services (IIS): Web server software for hosting and managing web applications.
- Virtual Private Network (VPN): Technology that creates a secure connection over the internet for remote access.
- Network Security Group (NSG): Azure feature that controls inbound and outbound traffic to resources.
- Wireshark: Network protocol analyzer used for monitoring and troubleshooting network traffic.
- Command Line Tools (CMD): Interface for executing commands and scripts in Windows environments.
- PowerShell (Administrator): Task automation and configuration management framework for Windows.
- Internet Control Message Protocol (ICMP): Network layer protocol used for diagnostic functions and error reporting.
- Secure Shell (SSH): Protocol for secure remote login and command execution on servers.

<h2>Operating Systems Used </h2>

- Windows 10 (21H2): Installed on a virtual machine for development and testing purposes.
- macOS Sonoma: The primary host operating system on the main computer.
- Linux (Ubuntu): Open-source operating system utilized for development and application tasks.

<h2>Post-Install Configuration Objectives</h2>

- Created resources and activities in Microsoft Azure to support application deployment.
- Configured a Virtual Private Network (VPN) within the virtual machine for secure connectivity.
- Implemented Network Security Groups (NSG) to manage and enforce network security policies.
- Analyzed network traffic using Wireshark to identify potential issues and optimize performance.
- Utilized command-line tools for in-depth analysis of network protocols.
- Monitored ICMP traffic and verified connectivity using the ping command.
- Administered Secure Shell (SSH) access through the command line for secure remote management.
- Set up Remote Desktop Protocol (RDP) connections for VM1 and VM2, while monitoring traffic between them.

<h2>Configuration Steps</h2>

<p>
<img src="https://github.com/user-attachments/assets/665fcabd-0896-4ed5-8b3d-b4e606196b7c"/>
</p>
<p>
1.	Created resources and activities in Microsoft Azure: Developed a structured environment to facilitate application deployment and management within the Azure cloud platform.
2.	Set up a Virtual Private Network (VPN) in the Azure cloud tenant: Established a secure VPN connection to enable encrypted communication between on-premises resources and Azure, ensuring data privacy and security.
3.	Established a resource group and subnet: Organized resources into a dedicated resource group for better management and applied a subnet configuration to segment the network for improved performance and security.
4.	Deployed VM1 (Windows) and VM2 (Linux) within the resource group: Provisioned a Windows virtual machine (VM1) for Windows-based applications and a Linux virtual machine (VM2) for development and testing purposes, optimizing for diverse workloads.
5.	Configured a Network Security Group (NSG): Set up an NSG to define inbound and outbound security rules, controlling access to resources within the network and enhancing overall security posture.

</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/70cc655e-5d87-4457-abcb-524c1d7861d7"/>
</p>
<p>
Used Wireshark to analyze network traffic. In the Windows Command Line Tool, checked the network protocols such as the tenant, subnet, and the 2 virtual machines being monitored.  
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/05ef2a2d-4122-419d-b594-fbc64b0ed5ef"/>  
</p>
<p>
Viewed ICMP through Wireshark. Implemented ping command to test connectivity between VM1 and VM2. Used Remote Desktop Protocol for VMs in my host computer (macOS). 
</p>
<br />
